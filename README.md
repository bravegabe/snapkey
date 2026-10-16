<p align="center"><img src="images/icon.png" width="128" alt="Snapkey icon"></p>

<h1 align="center">Snapkey®</h1>

<p align="center"><b>Screenshots with one finger.</b><br>
Tap one key, drag, release. The shot is on your clipboard.</p>

<p align="center"><a href="https://github.com/bravegabe/snapkey/releases/latest"><b>Download for Mac</b></a><br>
<sub>macOS 13 or later · Apple silicon and Intel · signed and notarized</sub></p>

![Snapkey capturing part of a window](images/snapkey-in-action.png)

## Why

macOS can already copy a region of the screen to the clipboard, but the shortcut is a four-key chord (⌃⇧⌘4) that takes a whole hand and pulls you out of what you're doing.

Snapkey® turns it into a single tap of one modifier key, such as Right Command, the key sitting just above the trackpad. Your hand never leaves the trackpad.

## How it works

1. **Tap** your capture key on its own.
2. **Drag** over what you want and release.
3. **Paste** with ⌘V.

Press Esc to cancel a capture. **Double-tap** the key to capture the same area as last time, with no dragging, which is handy for a quick before and after. Normal shortcuts that use the same key (⌘C, ⌘V and so on) are ignored; only a quick solo tap triggers a capture.

## Batch several shots into one paste

Tap a second key (Right Option by default) and the next shot is **added** to the clipboard instead of replacing it. There's no limit: grab as many as you need, paste once, and they all land together.

While a batch is on your clipboard, the menu bar icon shows how many shots are in it.

Snapkey doesn't cap a batch, but the app you paste into may: some take every image, some cap how many they accept at once, and others take only the first.

## Lives in the menu bar

![Snapkey menu](images/snapkey-menubar.png)

Choose your capture key and your add-to-batch key, and turn on Launch at Login. There are no other windows or settings.

## Updates

Snapkey checks once a day for a new version and shows you what changed, with a button to download it. You can turn the check off in the menu.

## Install

![Snapkey in Launchpad](images/snapkey-launchpad.png)

Snapkey is signed by Brave People, LLC and notarized by Apple, so it opens without security warnings.

1. Download the DMG from the [latest release](https://github.com/bravegabe/snapkey/releases/latest).
2. Open it and drag Snapkey to Applications.
3. Launch Snapkey. The welcome window walks you through the one permission it needs.

## Permission

Snapkey needs **Screen Recording** access, which macOS requires of any app that captures the screen. It only captures when you tap its key, and the image goes straight to your clipboard. Your screenshots never leave your Mac. Snapkey goes online for two things only:

- **Update check.** Once a day it asks GitHub for the latest version number.
- **Anonymous usage counts.** Once a day it reports how many captures, batch adds and re-shoots you made, along with the app version, the macOS version and a random install number. It never sends screenshots or anything about what is on your screen, and nothing identifies you. Turn it off with **Share Anonymous Usage Stats** in the menu.

---

<sub>Made by <a href="https://bravepeople.co">Brave People</a>. © 2026 Brave People, LLC. The images above are illustrations.</sub>
