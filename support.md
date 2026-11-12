---
title: Support
description: Setting up Ice Tray, how the freeze works, fixes, and Ice Tray Pro.
permalink: /support/
---

# Ice Tray support

## Setting up

Ice Tray freezes the apps you choose through one shortcut in Apple's Shortcuts app, called **Ice Tray**. One shortcut
freezes all your apps. It needs iOS 27.2 or later.

1. In Ice Tray, tap **Choose Apps** (or **Choose Your Apps** when you first open it). Shortcuts opens Ice Tray's
   ready-made shortcut and asks "Which apps do you want to freeze?". Choose them, and turn on **Automation**.
2. Tap **Add Shortcut**. That's all: the rest of the shortcut is already in place.
3. Open one of the apps you chose. It'll be frozen.

To **add or remove apps** later, tap **Choose Apps** in Ice Tray, then **Open Shortcut**. At the top of the Ice Tray
shortcut, "When [your apps] is Opened", tap **+** to add an app. Tap an app to change or remove it. Keep the shortcut's
name **Ice Tray**: Ice Tray uses it to find the shortcut.

### Set It Up Yourself

To make the shortcut by hand instead, tap **Set It Up Yourself** in Ice Tray: it shows the finished shortcut, step by
step. Here it is in full:

1. **When** [your apps] **is Opened**: in Shortcuts, tap **Automation**, then **+** and **App**. Pick your apps, choose
   **Is Opened** and **Run Immediately**, then start a new blank automation.
2. **Text**: add a **Text** action. In it, put the trigger's **App**, type **|** (no spaces), then put the **App**
   again. Tap the first **App** and choose **Name**; tap the second and choose **Bundle Identifier**. It reads
   "App Name|App Bundle Identifier".
3. **Ice Tray: Unfreeze [Text]**: add Ice Tray's **Unfreeze**. Touch and hold **Which App** and choose the **Text**
   from step 2 (not the trigger's App).
4. **If** Ice Tray is **Open** → **Open App** (the trigger's **App**); **Otherwise** → **Go to Home Screen**.

Last, name it **Ice Tray**, and in **ⓘ** → **Privacy** turn on **Allow Running When Locked**, so it runs without asking.

Why the Text step: Shortcuts doesn't hand the trigger's App straight to Ice Tray, but it does hand over text. The Text
step tells Ice Tray the app's name (what it shows) and its bundle ID (how it knows the app, and how it finds the app's
icon).

## How the freeze works

- A frozen app shows as ice holding its icon. Breathe in as the ice rises; breathe out, slowly, and it melts, half with
  each breath out. 2 slow breaths, about 21 seconds. There's no button to skip it: that's the point. Swiping home
  leaves, and counts as putting the app back.
- When the ice is gone the icon sits in a little puddle, and it's your call. **Put It Back** drops the icon back into
  the ice, leaves the app closed and takes you to your Home Screen. **Open** _the app_ (the line under it) opens it.
  The first time, iOS may ask whether Ice Tray may open the app: tap **Open**.
- **Choose within a few seconds of the ice melting.** Shortcuts stops an action after 30 seconds. If you wait longer,
  the shortcut ends quietly, but Ice Tray keeps both buttons on screen: **Open** still opens the app (or tells you it's
  ready), and **Put It Back** goes to Ice Tray's home.
- After you open an app, it stays unfrozen for 2 minutes: open it again and it opens straight away, with no breath.
- Ice Tray never stops you opening anything. It gives you a moment first.
- Home tells you your week in one sentence: how many times you reached for a frozen app, and how many times you put it
  back. Then "Nice work.", because taking the moment is the point, whichever you chose. It's kept on your iPhone for 8
  weeks and goes nowhere else.
- There's no Siri or Spotlight phrase for Ice Tray: a freeze needs an app, so it only happens through the shortcut.

## It isn't working

- **Nothing happens when I open the app.** In Shortcuts, check the Ice Tray shortcut is added and the app is in its
  trigger (**Choose Apps** in Ice Tray opens it).
- **Ice Tray breathes but never asks about the app, and shows no app name.** The shortcut isn't handing Ice Tray the
  app. In the Ice Tray shortcut, check there's a **Text** step holding the trigger's App **Name**, **|** and App
  **Bundle Identifier**, and that Ice Tray's **Unfreeze** has the **Text** as its **Which App** (see Set It Up
  Yourself). Or add Ice Tray's shortcut again from **Choose Apps**: it comes with the Text step.
- **I chose Open and the app didn't open, or Ice Tray says the app "is ready".** Your Ice Tray shortcut has no **If Ice
  Tray is Open → Open App**, or you waited too long to choose (above). Open the app yourself: for 2 minutes after you
  chose Open it opens without a breath. To fix it, add Ice Tray's shortcut again from **Choose Apps**, or follow
  **Set It Up Yourself**.
- **I chose Put It Back and stayed in Ice Tray.** Your shortcut has no **Otherwise → Go to Home Screen**, or you waited
  more than a few seconds to choose (above). Add it under **Otherwise**, or add the shortcut again.
- **The app opens with nothing shown.** Either you chose Open for it in the last 2 minutes, or it isn't frozen: without
  Ice Tray Pro only the app with the checkmark on home is frozen; with Ice Tray Pro, check its switch on home is on.
- **An app shows a letter instead of its icon.** Ice Tray gets icons from Apple's App Store. Some of Apple's own apps
  aren't there, and with no connection there's nothing to fetch, so Ice Tray shows a frosted tile with the app's first
  letter. It tries again later.
- **An app I hid came back.** **Hide** only takes an app off the list on home; the shortcut still covers it, so it comes
  back the next time it's opened and it stays frozen. To stop freezing it, switch it off on home (Ice Tray Pro) or
  remove it in the shortcut.
- **No haptics.** Check **Haptics** in Ice Tray's Settings (the gear).

## Ice Tray Pro

- **Free:** the freeze for 1 app, marked with a checkmark on Ice Tray's home. It's the first app your shortcut hands
  Ice Tray, until you tap another app on home to freeze it instead. Every other app opens normally, with nothing shown.
  The other apps stay in the shortcut, so nothing needs removing.
- **Ice Tray Pro** freezes every app, and gives each one a switch on Ice Tray's home: switch an app off to let it open
  normally, and on again to freeze it, without touching the shortcut. US$0.99 a month or US$9.99 once, in the same
  digits in most currencies. The price in your currency is shown before you buy. Buy it from Ice Tray's Settings →
  **Ice Tray Pro**, or home's **Ice Tray Pro** row.
- **Restore:** Ice Tray's Settings → **Ice Tray Pro** → **Restore**, signed in with the Apple Account you bought with.
  Ice Tray also checks with the App Store each time it opens.
- **Cancel:** Ice Tray's Settings → **Manage Subscription**, or your iPhone's Settings → your name → **Subscriptions** →
  Ice Tray Pro. Cancel at least 24 hours before the current period ends to avoid the next charge; Ice Tray Pro lasts
  until then. The once-only purchase has nothing to cancel. Without Ice Tray Pro, Ice Tray keeps your switches but
  freezes just the 1 app again.
- **Family Sharing:** both plans can be shared with your Family Sharing group. Family members get Ice Tray Pro on their
  own iPhones (if sharing is turned on for it in your Apple Account's Family Sharing or Subscriptions settings) and
  can use Restore if it doesn't show up straight away.
- **Refunds** are handled by Apple: [reportaproblem.apple.com](https://reportaproblem.apple.com).

## Privacy

No account, no tracking, no data collected. Ice Tray keeps your apps' names and bundle IDs on your iPhone, and asks
Apple's App Store for their icons, sending only each app's bundle ID and your region; nothing reaches us. See the
[privacy policy]({{ '/privacy/' | relative_url }}).

## Contact

Email [apphazardstudios@gmail.com](mailto:apphazardstudios@gmail.com).

Please say which iPhone and iOS version you have (Settings → General → About), and what you expected to happen. We
read every email and reply as soon as we can. Terms: see [Terms of use]({{ '/terms/' | relative_url }}).
