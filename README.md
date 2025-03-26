# 0xilis's Tweak Repository
My repository for my tweaks

# Tweaks:

## LetMePass

Bypasses YouTube "Update Required" alert.

### Changelog:

**LetMePass 1.4:** armv7 support.

**LetMePass 1.3:** Even more optimized, plus iOS 10 support.

**LetMePass 1.2:** Optimizations and bugfixes.

**LetMePass 1.1:** Fix localization bugs.

**LetMePass 1.0.0:** First version.

**Source:** [https://github.com/0xilis/LetMePass](https://github.com/0xilis/LetMePass)

## Safecuts

Fix iOS 15.0-15.3.1 shortcuts hide action vuln.

**Source:** [https://github.com/0xilis/Safecuts](https://github.com/0xilis/Safecuts)

### Changelog:

**Safecuts 1.1:** Now filters WFControlMode in repeat.each as well, plus now also hooks WFExtractShortcutResult so unsigned shortcut files should also now be protected with Safecuts. Should also use objc-api only now so shouldn't depend on Substrate.

**Safecuts 1.0.0:** First version.

## Badger

Notification badges. Reimagined.

Badger is not on this repo at the moment, it's on Havoc. Please add [https://havoc.app](https://havoc.app). It will later migrate to this repo.

Semi-Open Source, tweak side is currently not, however BadgerApp is [https://github.com/0xilis/BadgerApp](https://github.com/0xilis/BadgerApp). BadgerPrefs also shows some of the preference handling tweak-side (which, just a warning, currently is the worst part of the entire source code, really need to rewrite it at some point...), look if you dare: [https://github.com/0xilis/BadgerPrefs](https://github.com/0xilis/BadgerPrefs).

For Badger 1.2.2 Beta 5, reach out to me and I'll probably provide it to you.

## Pastcuts

Import iOS 15 shortcuts on iOS 14 and iOS 13

Pastcuts is no longer on this repo and has moved to Havoc. However, old versions are kept here for archival purposes. Still though, I would advise using the newest version available on Havoc.

**Source:** [https://github.com/0xilis/Pastcuts](https://github.com/0xilis/Pastcuts)

### Changelog:

**Pastcuts 1.2.2:** Changed the old and bad icon I did in 1.2.1 to a much better icon by someone else. Also, default version for version spoofing is now 15.4.1 instead of 15.4.

**Pastcuts 1.2.1:** Added an icon for Pastcuts.

**Pastcuts 1.2.0:** Pastcuts now changes some iOS 15 actions to their iOS 13/14 equivalents! This should support Return to Homescreen, Select File, Stop and Output, and the iOS 15 version of Get File. This also allows you to specify what you want to spoof as the version. Pastcuts is also open source now!

**Pastcuts 1.1.2:** Switched to using WFSharedShortcut as it's much safer, and better for performance. also version spoofing now spoofs 15.4 rather than 15.3.1.

**Pastcuts 1.1.1:** should clean up some things and fix minor bugs, as well as now logs installs for stats

**Pastcuts 1.1.0:** Added version spoofing, can be turned off if you want

**Pastcuts 1.0.0:** First version.

## Pastcuts12

Import iOS 16/15/14/13 shortcuts on iOS 12 and Workflow

## Springlicious

FOSS SpringBoard Customization Tweak

### Changelog:

**Springlicious 1.1:** Hide Dock's BG only, Status Bar Opacity, Battery Percent in battery symbol for notched devices, customizable battery colors, and more. Major update, lots of new features and bug fixes.

**Springlicious 1.0.1:** Improvements to preferences and color management (thanks ryannair05!). Cephei should no longer be a dependency.

**Springlicious 1.0.0:** First version.

## Importcuts

Import .shortcut files, even when unjailbroken

## ReturnGetVariable

Unhide the Get Variable action on iOS 13.0-14.4.2

### Changelog:

**ReturnGetVariable 1.0.1:** Now logs for installs.

**ReturnGetVariable 1.0.0:** First version.

## StopShortcutsUntitledPrompt

Stop being forced to name shortcuts

## NoYTAds

No ads in YouTube

## BypassZoomDetection

Stop getting the "jailbreak detected" alert on Zoom

## HideMyVPN

Hides VPN from status bar (Note: Springlicious has this exact same funcitonality built in along with other options, I'd recommend switching to Spirnglicious)

## NoPendingRequests

Hide Pending Requests in insta (note: may not work anymore and I'm not updating this)

## NoPromotedTweets

No promoted tweets. Sadly only works in older versions of the twitter app.

# Tools:

## shortcut-sign

Open-Source Signed Shortcut CLI tool

**Source:** [https://github.com/0xilis/shortcut-sign](https://github.com/0xilis/shortcut-sign)

## neoaa

Open-Source Apple Archive CLI tool

**Source:** [https://github.com/0xilis/neoaa](https://github.com/0xilis/neoaa)

## appleid-key-dumper

Apple ID Key/Cert dumper for jailbroken iOS. (For use in shortcut-sign)

**Source:** [https://github.com/0xilis/appleid-key-dumper](https://github.com/0xilis/appleid-key-dumper)

# Libraries:

## libNeoAppleArchive

Cross-compat library for parsing Apple Archive + Apple Encrypted Archive (.aar/.yaa/.aea).

**Source:** [https://github.com/0xilis/libNeoAppleArchive](https://github.com/0xilis/libNeoAppleArchive)

## libshortcutsign

Library for signed shortcuts.

**Source:** [https://github.com/0xilis/libshortcutsign](https://github.com/0xilis/libshortcutsign)
