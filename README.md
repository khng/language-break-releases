# LanguageBreak

A macOS menu bar app that turns breaks into short, fullscreen flashcard sessions for whatever language you're learning. Every hour of activity it takes over the screen for a minute of spaced-repetition review, then gets out of the way. You bring the words (an Anki deck or a spreadsheet).

This repository only hosts the releases.

## Install

1. Download the `.dmg` from the [latest release](https://github.com/khng/language-break-releases/releases/latest) (macOS 26 or later; Apple silicon or Intel).
2. Open it and drag **LanguageBreak** to Applications.
3. The first time you open it, macOS says it can't verify the developer (the app isn't notarized). Click **Done**, then go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.
4. A welcome window walks you through choosing your language and adding words.

After that it updates itself: once a day it checks for a new version here and offers to install it (Settings → General turns this off). Updates are verified with a signing key before they're installed.
