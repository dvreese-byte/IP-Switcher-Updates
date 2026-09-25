# IP Switcher update feed

This public repository contains only a version number for the private IP Switcher application. It contains no IP presets, source code, or installer files.

After publishing a new installer ZIP as a release in the private `dvreese-byte/IP-Switcher` repository, change `latest.json` to the released assembly version (for example, `2.4.0.0`). The app checks this file on startup and offers **Get update** in Settings when the version is newer than the installed app. Update the feed only after the release is available to employees.
