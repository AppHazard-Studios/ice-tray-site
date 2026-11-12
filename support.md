---
title: Support
description: Setting up Ice Tray, how the freeze works, fixes, and Ice Tray Pro.
permalink: /support/
---

# Ice Tray support

## Setting up

Ice Tray freezes the apps you choose through one shortcut in Apple's Shortcuts app, called **Ice Tray**. One shortcut
freezes all your apps. It needs iOS 27.2 or later.

1. In Ice Tray, tap **Add to Shortcuts**. Shortcuts opens Ice Tray's ready-made shortcut and asks "Which apps do you
   want to freeze?". Choose them, and turn on **Automation**.
2. Tap **Add Shortcut**.
3. Open one of the apps you chose. It'll be frozen.

To **add or remove apps** later, tap **Add or Remove Apps** in Ice Tray, then **Open Shortcut**. At the top of the Ice
Tray shortcut, "When [your apps] is Opened", tap **+** to add an app. Tap an app to change or remove it. Keep the
shortcut's name **Ice Tray**: Ice Tray uses it to find the shortcut.

To make the shortcut yourself instead, tap **Set It Up Yourself** in Ice Tray. It shows the finished shortcut, action by
action: the trigger "When [apps] is Opened", then Ice Tray's action, **Unfreeze [App]**, with its **Which App** set to
the trigger's **App**, then **If** Ice Tray is **Open** → **Open App**. Also turn on **Allow Running When Locked**, in
the shortcut's ⓘ → **Privacy**, so it runs without asking. Name the shortcut **Ice Tray**.

## How the freeze works

- A frozen app shows as ice holding its icon. You breathe in as the ice rises and out as it falls and melts: 2 slow
  breaths, about 21 seconds. There's no button to skip it: that's the point. Swiping home leaves, and counts as putting
  the app back.
- Then it's your call. **Put It Back** leaves the app closed. **Open** _the app_ opens it. The first time, iOS may ask
  whether Ice Tray may open the app: tap **Open**.
- **Choose within a few seconds of the ice melting.** Shortcuts stops an action after 30 seconds. If you wait longer,
  the shortcut ends quietly, but Ice Tray keeps both buttons on screen: **Open** still opens the app (or tells you it's
  ready), and **Put It Back** goes to Ice Tray's home.
- After you open an app, it stays unfrozen for 2 minutes: open it again and it opens straight away, with no breath.
- Ice Tray never stops you opening anything. It gives you a moment first.
- Home tells you your week in one sentence: how many times you reached for a frozen app, and how many times you put it
  back. It's kept on your iPhone for 8 weeks and goes nowhere else.
- There's no Siri or Spotlight phrase for Ice Tray: a freeze needs an app, so it only happens through the shortcut.

## It isn't working

- **Nothing happens when I open the app.** In Shortcuts, check the Ice Tray shortcut is added and the app is in its
  trigger (**Add or Remove Apps** in Ice Tray opens it).
- **Ice Tray breathes but never asks about the app, and shows no app name.** The shortcut isn't handing Ice Tray the
  app. In the Ice Tray shortcut, set Ice Tray's action, **Unfreeze [App]**, to the trigger's **App** (its **Which App**).
- **I chose Open and the app didn't open, or Ice Tray says the app "is ready".** Your Ice Tray shortcut has no **If Ice
  Tray is Open → Open App**, or you waited too long to choose (above). Open the app yourself: for 2 minutes after you
  chose Open it opens without a breath. To fix it, add Ice Tray's shortcut again from **Add to Shortcuts**, or follow
  **Set It Up Yourself**.
- **The app opens with nothing shown.** Either you chose Open for it in the last 2 minutes, or it's past your free app:
  Ice Tray's home lists those as "Not frozen" (see Ice Tray Pro).
- **An app I hid came back.** **Hide** only takes an app off **In the tray**; the shortcut still covers it, so it comes
  back the next time it's opened and it stays frozen. To stop freezing it, remove it in the shortcut.
- **No haptics.** Check **Haptics** in Ice Tray's Settings (the gear).

## Ice Tray Pro

- **Free:** the freeze for 1 app. It's the first app your shortcut hands Ice Tray, until you choose another by tapping
  it on home (every app past the free one is listed as "Not frozen", and opens with nothing shown). The other apps stay
  in the shortcut, so nothing needs removing.
- **Ice Tray Pro** unlocks the full tray, so every app you choose is frozen: US$0.99 a month or US$9.99 once, in the
  same digits in most currencies. The price in your currency is shown before you buy. Buy it from Ice Tray's Settings →
  **Ice Tray Pro**.
- **Restore:** Ice Tray's Settings → **Ice Tray Pro** → **Restore**, signed in with the Apple Account you bought with.
  Ice Tray also checks with the App Store each time it opens.
- **Cancel:** Ice Tray's Settings → **Manage Subscription**, or your iPhone's Settings → your name → **Subscriptions** →
  Ice Tray Pro. Cancel at least 24 hours before the current period ends to avoid the next charge; Ice Tray Pro lasts
  until then. The once-only purchase has nothing to cancel.
- **Family Sharing:** both plans can be shared with your Family Sharing group. Family members get Ice Tray Pro on their
  own iPhones (if sharing is turned on for it in your Apple Account's Family Sharing or Subscriptions settings) and
  can use Restore if it doesn't show up straight away.
- **Refunds** are handled by Apple: [reportaproblem.apple.com](https://reportaproblem.apple.com).

## Privacy

No account, no tracking, no data collected. Ice Tray asks Apple's App Store for your apps' icons, sending only each
app's ID or name and your region; nothing reaches us. See the [privacy policy]({{ '/privacy/' | relative_url }}).

## Contact

Email [apphazardstudios@gmail.com](mailto:apphazardstudios@gmail.com).

Please say which iPhone and iOS version you have (Settings → General → About), and what you expected to happen. We
read every email and reply as soon as we can. Terms: see [Terms of use]({{ '/terms/' | relative_url }}).
