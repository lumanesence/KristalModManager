# KristalModManager
A super simple mod manager for the Kristal DELTARUNE engine written in Python, with support for installing, uninstalling, viewing and editing the metadata installed mods, as well as providing a system to load and run Kristal right from there (to be added), making it an all-in-one solution for both managing mods and opening Kristal!

## The Featureset
* Install new Kristal mods through a local .zip file or via a URL!
* View, delete and fill in missing information on your current mods! (might break them in some rare cases)
* Load Kristal without needing to locate it every single time!

## Why bother?
**Why not!** - My reason for making this is very simple, actually. To install a mod with Kristal, you need to go into your device's AppData Roaming folder, then place the mod right in there. Understandably, some people don't know their way around the Windows filesystem, meaning they usually refrain from going in there, and that's okay! Thats why this exists, to make it easier for you to manage your installed Kristal mods and even install new ones if you want to!

## Does it actually work?
**Yes, it does!** - the way it works is by unzipping the mod directly into your Kristal directory in your AppData folder, which will make the mod accessible from within Kristal! As for deleting, it deletes the mod folder from your Kristal directory in a near-instant[1], making it easy to both delete and install mods! [Click here for a demonstration video!](https://youtu.be/ANHZu-uf60Q)

## When is it releasing?
Currently, I'm still heavily working on it inbetween my college studies, and due to recent shake-ups regarding my GCSE retakes, I have no projection for a release date. The same goes for pre-releases, although you may get a few of those dotted around. If you want updates on it's development however, check out my Infocentre on Discord where project updates will be posted: https://discord.gg/XZNxe8tfaX

## Confirmed dependencies
* pygame


**Don't worry!** If you *do not* have Pygame installed already, the script will install it for you; thats how simple this is, you don't have to worry about that!

## Credits
* KristalModManager: Me! (Lumanesence)
* Kristal Engine: https://kristal.cc
* BGM: Central Independent Television - Central Fanatasia (1982 Edition)

## Disclaimers
* KristalModManager is in no way associated with the Kristal developers and is purely a fan project
* Editing mods using the "Fill In" function has the possibility to break a mod in it's entirety, which will require it to be reinstalled
* This software is licensed under the MIT License. You may modify and redistribute these files **if credit is provided**, but is provided as-is with no warranties or guarantees. All later iterations not made by me must be licensed under the MIT License regardless of how transformative your changes are.
* KristalModManager only works on Windows-based systems with x64, x86 and Arm64 based CPU's. Mac and Linux versions are not planned at ths time

*Copyright 2025 The OneLyte Association - All Rights Reserved*

### Footnotes
[1]: Deleting a folder may vary on your device's specification, specifically read and write speeds
