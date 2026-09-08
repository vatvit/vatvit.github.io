---
title: Dark Maze — Privacy Policy
description: Dark Maze collects nothing, sends nothing, and this is what it keeps on your own device.
permalink: /dark-maze/privacy/
---

# Privacy Policy for Dark Maze

**Last updated: 8 September 2026**

## The short version

**Dark Maze does not collect, transmit or share any information about you.**

There is no account, no sign-in, no server, no analytics, no advertising and no crash reporting in
the game, and nothing in it reports to anybody. Nothing you do is sent anywhere, because there is
nowhere for it to be sent to.

This is not a promise about how we intend to behave. It is a description of how the game is built,
and the rest of this page says exactly what that means.

## What the game keeps, and where

The game remembers a few things between sessions so it does not have to ask you twice. All of it is
stored **on your own device** — in your browser's local storage on the web version, and in the
app's own private storage on the desktop and Android versions. None of it leaves the device.

| What is remembered | Why |
|---|---|
| Whether the opening sequence has played | So it does not replay every launch |
| The video mode you picked | So the game looks the way you left it |
| The sound card you answered | So the hardware menu does not ask again |
| Your two volume settings | So the game sounds the way you left it |
| The high score table — ten scores, with the three letters entered for each | So a good run is still there tomorrow |

**Those three letters are the only thing in the game that you write yourself.** They are yours, they
stay on your device, and nobody else — including us — ever sees them. You can type anything you
like there.

## How to erase all of it

You do not need to ask us, because we do not hold it.

- **In a browser:** clear the site data for the page the game is on, through your browser's normal
  settings. The game returns to its defaults.
- **On desktop or Android:** uninstall the game, or clear the app's data through your operating
  system.

That is the whole of it. There is no request to make, no form, and no waiting period, because there
is no copy of anything anywhere else.

## Why the game cannot send anything, even by accident

Software that says it sends nothing usually still *could*. This one mostly cannot, and the reasons
are checkable:

- **The Android app has no internet permission.** Its manifest requests none, so Android itself
  refuses the app a network connection. This is enforced by your phone, not by us.
- **The desktop app is locked to its own files.** Its content-security policy is
  `default-src 'none'` with connections restricted to itself, so it cannot reach any outside
  address.
- **The game bundles no reporting code.** There is no analytics library, no advertising SDK and no
  crash reporter anywhere in the build. The desktop and Android versions are wrapped in Tauri and
  Capacitor respectively, which are third-party software, but neither is configured to send
  anything and neither is given anywhere to send it to.
- **The browser version loads only its own files.** It requests no fonts, scripts or images from any
  outside address.

## Children

The game collects no information from anyone, and that includes children. Because nothing is
collected, stored remotely or shared, there is nothing about a younger player that could be
gathered, profiled or passed on.

The game contains dark and tense moments; whether it suits a particular child is a judgement for
that child and the people who look after them, and age ratings on each store are there to help with
it. That is a question about content, not about privacy, and this policy takes no position on it.

## What the shop knows, which is not us

If you bought or installed Dark Maze from a store — itch.io, Steam, Google Play, the Apple App
Store — **that store handled your purchase and your account, and it collects data in doing so**,
under its own privacy policy rather than this one. That can include your payment details, your
account identity, your device and your country.

Most of what a store holds never reaches us — we see sales and install counts that identify
nobody. **Some stores do pass on a little more**, and the usual case is an email address attached
to a purchase, so that a seller can deal with a support question or a refund. Where a store gives
us that, we use it only to answer you. We do not add it to a mailing list, we do not use it for
marketing, and we do not pass it to anyone else.

If you want to know what a store keeps about you, its own privacy policy is the document that
answers that, and this one cannot speak for it.

## If this ever changes

If crash reporting, analytics or any other form of data collection is ever added to Dark Maze,
**this document is the first thing that changes** — updated and republished before a build
containing it is released, with the date at the top of this page changed to match.

We will not add silent collection to an existing version. A page that says "we may update this
policy from time to time" and leaves it there is doing the opposite of what a privacy policy is
for.

## Contact

Questions about this policy, or about anything on this page:

**vatvit.dev+darkmaze@gmail.com**
