---
title: Support
description: Setting up Thaw, how the pause works, fixes, and Thaw Pro.
permalink: /support/
---

# Thaw support

## Setting up

Thaw breathes with you before the apps you choose, through one shortcut in Apple's Shortcuts app (iOS 27 or later).
Its automation is the trigger at the top of the shortcut: **When** _your apps_ **is opened** → **Take a Breath**
(App: the trigger's App).

1. In Thaw, tap **Set Up** (or **Add to Shortcuts** when you first open Thaw). Shortcuts opens Thaw's ready-made
   shortcut, called **Thaw**.
2. Turn on **Automation** and tap **Add Shortcut**. If Shortcuts asks which apps Thaw should pause, choose them there.
3. Otherwise, back in Thaw, tap **Open Thaw's Shortcut**. In the shortcut, tap **When … is opened** at the top, tap
   **Choose**, tick the apps you want a pause before, and tap **Done**. Thaw is ticked to start with; it never
   pauses itself.
4. Tap **▶** to come back to Thaw. Then open one of your apps: Thaw comes first.

To add or remove apps later, tap **Add or remove apps** in Thaw: it opens the Thaw shortcut, where you tick or untick
apps in its trigger. To remove one, untick it, then swipe it away under **Your apps** in Thaw. Keep the shortcut's
name **Thaw**: Thaw uses it to find the shortcut, and to open some apps after the breath.

To make the shortcut yourself instead, tap **Set it up yourself** in Thaw: one new shortcut named **Thaw**, with
**Automation** → **App** (your apps, **Is Opened**, **Notify** off), the action **Take a Breath** with its App set to
the trigger's **App**, and ⓘ → **Privacy** → **Allow Running When Locked** so it runs without asking.

## How the pause works

- Two slow breaths, about 21 seconds. There's no button to skip it: that's the point. Swiping home leaves, and
  counts as not opening the app.
- Then you choose. **I don't want to open** _the app_ leaves it closed, and Thaw settles back to its home.
  **Continue to** _the app_ opens it. The first time Thaw opens each app, iOS asks whether Thaw may open it: tap
  **Open**. It only asks once per app.
- Back within two minutes of choosing Continue, that app opens straight away, with no breath.
- From Siri ("Take a breath with Thaw"), Spotlight, the Action button or Thaw's own **Take a Breath** button there's
  no app, so there's no choice: just the breath.

## It isn't working

- **Nothing happens when I open the app.** In Shortcuts, check the Thaw shortcut's **Automation** is on and the app is
  ticked in its trigger (**Add or remove apps** in Thaw opens it).
- **Thaw breathes but never asks about the app, and shows no app name.** The automation isn't handing Thaw the app.
  In the Thaw shortcut, set Take a Breath's **App** to the trigger's **App**.
- **Shortcuts appears for a moment after Continue.** For apps Thaw has no direct link to, it opens them by running
  your Thaw shortcut. That's expected.
- **Thaw says the app "is ready" instead of opening it.** Thaw has no direct link to that app and no Thaw shortcut
  to open it with (you set up by hand, or renamed the shortcut). Open the app yourself: for two minutes after Continue
  it opens without a breath.
- **The app opens without a breath.** Either you chose Continue for it in the last two minutes, or it's past your 3
  free apps: Thaw's home lists those as "Opens without a pause" (see Thaw Pro).
- **No haptics.** Check **Haptics** in Thaw's Settings (the gear).

## Thaw Pro

- **Free:** the pause before 3 apps: the first three different apps your automation hands Thaw. To free a place,
  untick the app in the Thaw shortcut, then swipe it away under **Your apps**. The breath on its own is always free.
- **Pro** pauses unlimited apps: US$2.99 a month, US$14.99 a year (the first week free), or US$39.99 once.
  Prices in your currency are shown before you buy. Buy it from Thaw's Settings → **Thaw Pro**.
- **Restore:** Thaw's Settings → **Thaw Pro** → **Restore**, signed in with the Apple Account you bought with. Thaw
  also checks with the App Store each time it opens.
- **Cancel:** Thaw's Settings → **Manage Subscription**, or your iPhone's Settings → your name → **Subscriptions** →
  Thaw Pro. Cancel at least 24 hours before the trial or the current period ends to avoid the next charge; Pro lasts
  until then. Lifetime is a single purchase with nothing to cancel.
- **Family Sharing:** all three plans can be shared with your Family Sharing group. Family members get Pro on their
  own iPhones (if sharing is turned on for it in your Apple Account's Family Sharing or Subscriptions settings) and
  can use Restore if it doesn't show up straight away.
- **Refunds** are handled by Apple: [reportaproblem.apple.com](https://reportaproblem.apple.com).

## Privacy

No account, no tracking, no data collected. Thaw asks Apple's App Store for your apps' icons, sending only each
app's ID or name and your region; nothing reaches us. See the [privacy policy]({{ '/privacy/' | relative_url }}).

## Contact

Email [apphazardstudios@gmail.com](mailto:apphazardstudios@gmail.com).

Please say which iPhone and iOS version you have (Settings → General → About), and what you expected to happen. We
read every email and reply as soon as we can. Terms: see [Terms of use]({{ '/terms/' | relative_url }}).
