# IP Switcher update feed

This public repository contains only a version number and installer SHA-256 checksum for the private IP Switcher application. It contains no IP presets, source code, or installer files.

After publishing a new installer ZIP in the company-only, view-only Microsoft 365 release folder and as a release in the private `dvreese-byte/IP-Switcher` repository, change `latest.json` to the released assembly version and ZIP checksum. The app checks this file on startup and offers **Update now** in Settings when the version is newer than the installed app. Update the feed only after both downloads are available. Do not put folder links, IP presets, or installer files in this public repository.
