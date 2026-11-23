# Ice Tray: public pages

The public website for **Ice Tray**, an iPhone app by AppHazard Studios: freeze the apps you doomscroll. Open one
and it's frozen in an ice cube; melt it with 2 slow breaths, then decide if you really want to open it. No account, no tracking, no data
collected. Free for 1 app; with Ice Tray Pro, freeze unlimited apps. The App Store listing is "Ice Tray: Stop
Doomscrolling". The app was called Thaw until 12
November 2026; the icon file keeps the `thaw` spelling.

This repository holds only the pages the App Store and the app link to. The app's code lives elsewhere.

| Page | Source | Published at |
|---|---|---|
| Home | [`index.md`](index.md) | https://apphazard-studios.github.io/ice-tray-site/ |
| Privacy policy | [`privacy.md`](privacy.md) | https://apphazard-studios.github.io/ice-tray-site/privacy/ |
| Terms of use | [`terms.md`](terms.md) | https://apphazard-studios.github.io/ice-tray-site/terms/ |
| Support | [`support.md`](support.md) | https://apphazard-studios.github.io/ice-tray-site/support/ |

Built by GitHub Pages with Jekyll: `_config.yml`, one layout in `_layouts/default.html` (system fonts, light and
dark, no scripts, no cookies, no analytics) and the icon in `assets/`. The front page's App Store button reads
`app_store_url` in `_config.yml`: empty shows "Coming soon to the App Store"; paste the app's link there once the App
Store record exists.

Voice: the front page and support are short and plain (only what someone comes for). The privacy policy and terms use
the standard structure and register of a real policy, and must match the App Store privacy label (Data Not Collected). How to publish it: [`PUBLISH.md`](PUBLISH.md).

Keep `privacy.md` and `support.md` true to the app: when the app's `docs/privacy.md`, `docs/support.md` or its
in-app privacy screen (`App/PrivacyView.swift`) change, change these too, and the other way round.

Contact: [apphazardstudios@gmail.com](mailto:apphazardstudios@gmail.com).

© AppHazard Studios. All rights reserved.
