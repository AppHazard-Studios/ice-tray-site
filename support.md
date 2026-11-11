---
title: Support
description: Setting up Thaw, how the pause works, fixes, and Thaw Pro.
permalink: /support/
---

# Thaw support

## Setting up

Thaw puts a pause before the apps you choose through one shortcut in Apple's Shortcuts app, called **Thaw**. One
shortcut covers all your apps. It needs iOS 27.2 or later.

1. In Thaw, tap **Add to Shortcuts** (or **Set Up** later). Shortcuts opens Thaw's ready-made shortcut and asks which
   apps Thaw should pause before. Choose them.
2. Turn on **Automation**, then tap **Add Shortcut**.
3. Open one of your apps. Thaw comes first.

To **add or remove apps** later, tap **Add or Remove Apps** in Thaw, then **Open Shortcut**. At the top of the Thaw
shortcut, "When [your apps] is Opened", tap **+** to add an app. Tap an app to change or remove it. Keep the shortcut's
name **Thaw**: Thaw uses it to find the shortcut.

To make the shortcut yourself instead, tap **Set It Up Yourself** in Thaw. It shows the finished shortcut, action by
action: the trigger "When [apps] is Opened", then Thaw's action "Take a breath before [App]" with its App set to the
trigger's **App**, then **If** Thaw's answer is **Open** → **Open [App]**, **Otherwise** → **Go to Home Screen**. Also
turn on **Allow Running When Locked**, in the shortcut's ⓘ → **Privacy**, so it runs without asking.

## How the pause works

- Two slow breaths, about 21 seconds. There's no button to skip it: that's the point. Swiping home leaves, and
  counts as not opening the app.
- Then you choose. **I don't want to open** _the app_ leaves it closed, and Thaw settles back to its home.
  **Continue to** _the app_ opens it. The first time, iOS may ask whether Thaw may open the app: tap **Open**.
- **Choose within a few seconds of the ice melting.** Shortcuts stops an action after 30 seconds. If you wait longer,
  the shortcut ends quietly, but Thaw keeps both buttons on screen: **Continue** still opens the app (or tells you
  it's ready), and **I don't want to open** goes to Thaw's home.
- Back within 2 minutes of choosing Continue, that app opens straight away, with no breath.
- From Siri ("Take a breath with Thaw"), Spotlight, the Action button or Thaw's own **Take a Breath** button there's
  no app, so there's no choice: just the breath.

## It isn't working

- **Nothing happens when I open the app.** In Shortcuts, check the Thaw shortcut's **Automation** is on and the app is in its trigger
  (**Add or Remove Apps** in Thaw opens it).
- **Thaw breathes but never asks about the app, and shows no app name.** The shortcut isn't handing Thaw the app. In
  the Thaw shortcut, set Thaw's action to **Take a breath before [App]** with the trigger's **App**.
- **I chose Continue and the app didn't open, or Thaw says the app "is ready".** Your Thaw shortcut has no **If Thaw's
  answer is Open → Open [App]**, or you waited too long to choose (above). Open the app yourself: for 2 minutes after
  Continue it opens without a breath. To fix it, add Thaw's shortcut again from **Set Up**, or follow **Set It Up
  Yourself**.
- **The app opens without a breath.** Either you chose Continue for it in the last 2 minutes, or it's past your 3
  free apps: Thaw's home lists those as "Opens without a pause" (see Thaw Pro).
- **An app I hid came back.** **Hide** only takes an app off Your apps; the shortcut still covers it, so it comes back
  the next time it's opened. To stop its pause, remove it in the shortcut.
- **No haptics.** Check **Haptics** in Thaw's Settings (the gear).

## Thaw Pro

- **Free:** the pause before 3 apps: the first 3 different apps your shortcut hands Thaw. To free a place, remove an
  app in the shortcut, then **Hide** it under **Your apps** in Thaw. The breath on its own is always free.
- **Thaw Pro** pauses more than 3 apps: US$2.99 a month, US$14.99 a year (the first week free), or US$39.99 once.
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
