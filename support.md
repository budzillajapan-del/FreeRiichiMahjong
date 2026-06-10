---
layout: page
title: Support
permalink: /support/
---

# MahjongmacOS Support

Thanks for playing! This page covers how to reach the developer and answers
to the most common questions.

## Get in touch

**Email:** [budzillajapan@gmail.com](mailto:budzillajapan@gmail.com)

I read every message. Whether it's a bug, a feature request, a rules
clarification, or just a hello — please write in. The app also has a
**Send Feedback** button on the Support sheet (main menu → heart icon)
that opens a pre-filled email with your app version attached.

When reporting a bug, the most useful things you can include are:

1. What you were trying to do
2. What happened instead
3. macOS version (Apple menu → About This Mac)
4. App version (visible at the bottom of the main menu)
5. A screenshot, if it's a visual issue

## Frequently asked questions

### Is the app really free?

Yes. MahjongmacOS is free and contains **no ads**, **no paywalls**, and
**no Pro version**. The full game is the only version. The optional tip
tiers in the Support menu are entirely voluntary and unlock nothing — the
app behaves identically whether you tip or not. See the
[privacy policy](https://budzillajapan-del.github.io/mahjongmacos/privacy) for full details.

### How do I sign in to Game Center?

Game Center sign-in is optional. To use it:

1. Open **System Settings → Game Center**.
2. Sign in with your Apple ID.
3. Open MahjongmacOS. You should see "Signed in to Game Center" on the
   main menu.
4. Click **Game Center — Quick Match** to find opponents.

If sign-in fails, the most common cause is that Game Center is restricted
for your Apple ID. Check **System Settings → Screen Time → Content &
Privacy Restrictions → Game Center**.

### My online match isn't finding opponents

Game Center turn-based matchmaking can take a few minutes during off-peak
hours. The app supports 2-4 player matches. If you've been waiting more
than 5 minutes, try **End Match** and start a new one — Apple's matchmaker
sometimes works better with a fresh request.

### Local Network play isn't finding anyone on my Wi-Fi

A few things to check:

1. **Both Macs must be on the same Wi-Fi network** (not on different
   networks at the same address, and not on the guest network on one
   and the main network on the other).
2. **Both Macs must have granted local network permission** to MahjongmacOS
   the first time the app asked. To re-grant: **System Settings → Privacy
   & Security → Local Network**, find MahjongmacOS, and enable it.
3. **Some routers block multicast (Bonjour) traffic**. If you're on a
   corporate or hotel network, this is often the cause. A home network
   usually works fine.

### How do I declare riichi?

When your hand is **closed** (no called melds) and you're **one tile away
from winning** (tenpai), a yellow **Riichi** button appears in your action
bar. Click it; the app will require you to discard a tile that keeps you
tenpai. Riichi costs 1000 points but adds 1 han and unlocks ura dora.

If the Riichi button doesn't appear: your hand probably isn't tenpai, or
you've called a meld during the hand (which closes off riichi).

### The AI is too easy / too hard

You can pick a difficulty when starting a Solo game:

- **Easy** — minimal defense, fast wins
- **Normal** — solid play, defensive at the basics
- **Hard** — reads opponent danger, plays safer
- **Expert** — infers opponent yaku from discards, plays tightest

Feedback on AI behaviour is genuinely useful — please write in if you find
a level that feels wrong.

### How do I see the yaku list during a game?

On the table, click the **menu icon (≡)** in the top-right corner. Choose
**Yaku Reference**. A scrollable list of every yaku appears with example
hands and han values.

You can also access the same reference from the main menu under **Learn →
Yaku Reference**.

### I tipped but the app still says "Thanks!" — did it work?

If the button shows a green checkmark with "Thanks!", the purchase
completed successfully. You'll receive an emailed receipt from Apple within
a few hours. Tips are processed entirely by Apple's App Store; the app
never sees your billing information.

If you accidentally tipped and would like a refund, you can request one
through Apple at <https://reportaproblem.apple.com>.

### How do I export or transfer my game?

There's currently no save export. Your in-progress game lives in the app's
local container on your Mac. If you upgrade to a new Mac, the easiest
path is to finish the current match before migrating.

### Where's the iPad / iPhone version?

Not yet. MahjongmacOS is currently macOS-only. iOS / iPadOS support is
something I'd love to add — it's a meaningful amount of work though, and
will only happen if there's demand. If you'd like it, write in and let
me know.

## System requirements

- **macOS 13** (Ventura) or later
- **Apple Silicon or Intel** Mac
- **Game Center sign-in** (optional, for online play only)
- **Local network permission** (optional, for LAN play only)
- **Internet connection** (only for Game Center matches)

## Privacy

See the [privacy policy](https://budzillajapan-del.github.io/mahjongmacos/privacy). Short version: the app collects no
data, runs no analytics, has no trackers, and ships no ads.

## Acknowledgements

The tile artwork is from the
[FluffyStuff/riichi-mahjong-tiles](https://github.com/FluffyStuff/riichi-mahjong-tiles)
project under CC0 1.0 Universal. Full credits are in the app's repository
[CREDITS.md](https://budzillajapan-del.github.io/mahjongmacos/CREDITS).

---

*MahjongmacOS · Copyright © 2026 Buddy Kinder. All rights reserved.*
