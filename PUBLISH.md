# Publishing Thaw's pages (owner)

About 15 minutes. Everything here is done by you, signed in to GitHub and App Store Connect. Nothing has been pushed
or created for you.

## 1. Create the public repository

On github.com, under **AppHazard-Studios**: **New repository**.

- Name: **`thaw-site`** (the URLs below assume this name; another name means changing `baseurl`, step 4)
- Visibility: **Public** (GitHub Pages on a free plan needs a public repository)
- Leave "Add a README", ".gitignore" and "license" **unticked** (this repository already has its files)
- **Create repository**

## 2. Push this folder

```bash
git -C ~/Developer/thaw-site remote add origin https://github.com/AppHazard-Studios/thaw-site.git
```

```bash
git -C ~/Developer/thaw-site push -u origin main
```

## 3. Turn on GitHub Pages

In the new repository: **Settings → Pages → Build and deployment**.

- Source: **Deploy from a branch**
- Branch: **main**, folder **/ (root)** → **Save**

The **Actions** tab shows "pages build and deployment"; it takes a minute or two. Then Settings → Pages shows
"Your site is live at https://apphazard-studios.github.io/thaw-site/".

## 4. Only if you used another name

If the repository isn't called `thaw-site`, edit `_config.yml`: `baseurl: /<the repository's name>`, commit and push.
If you later add a custom domain (Settings → Pages → Custom domain), set `url:` to it and `baseurl: ""`.

## 5. Check the pages

Open each one, on the iPhone too (Light and Dark):

- https://apphazard-studios.github.io/thaw-site/
- https://apphazard-studios.github.io/thaw-site/privacy/
- https://apphazard-studios.github.io/thaw-site/terms/
- https://apphazard-studios.github.io/thaw-site/support/

The icon shows at the top, the links between pages work, and there's no `{{` anywhere on the page.

## 6. Paste into App Store Connect

| Where in App Store Connect | Field | Paste |
|---|---|---|
| Your app → **App Information** (each localization) | **Privacy Policy URL** | `https://apphazard-studios.github.io/thaw-site/privacy/` |
| Your app → the 1.0 version → **App Store** tab | **Support URL** | `https://apphazard-studios.github.io/thaw-site/support/` |
| same | **Marketing URL** (optional) | `https://apphazard-studios.github.io/thaw-site/` |
| Your app → **App Information** | **License Agreement** | leave as **Apple's Standard License Agreement** (our terms page builds on it) |
| the 1.0 version → **Description**, last line | Terms of Use | keep `Terms of Use: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/`; you may add a line `Privacy: https://apphazard-studios.github.io/thaw-site/privacy/` |

Apple asks apps with subscriptions to link the Terms of Use (EULA) and the privacy policy both in the app (the
paywall does) and in the listing (the Privacy Policy URL field and the description's last line).

## 7. In the app's repository (tell the app session, or do it yourself)

- `docs/appstore/listing.md`, **URLs**: replace the two **PLACEHOLDER** lines with the privacy and support URLs above
  (`scripts/release-check.sh` fails until they're gone).
- `App/ThawLinks.swift`: nothing *has* to change for the site.
  - `ThawLinks.support` stays `mailto:apphazardstudios@gmail.com` (Settings → Contact Support).
  - `ThawLinks.terms` stays Apple's Standard EULA (the paywall's Terms of Use). Or point it at
    `https://apphazard-studios.github.io/thaw-site/terms/`, which links to the EULA; either is accepted.
  - Optional new constants, if the app should link to the pages: `ThawLinks.privacyPage` =
    `https://apphazard-studios.github.io/thaw-site/privacy/` and `ThawLinks.supportPage` =
    `https://apphazard-studios.github.io/thaw-site/support/` (for example for the privacy screen's Contact line,
    which today says "use the support link on Thaw's App Store page"). The paywall's Privacy Policy already opens the
    in-app privacy screen, so it needs no URL.
  - `ThawLinks.sharedShortcut` is a different thing: the iCloud link to the shared "Thaw" shortcut (owner item O3),
    not a page on this site.

## 8. Keeping it true

When Thaw changes what it keeps, sends or charges, update `privacy.md`, `terms.md` and `support.md` here in the same
week as the app's `docs/privacy.md`, `docs/support.md` and `App/PrivacyView.swift`, change the "Last updated" date,
then commit and push: Pages republishes by itself.
