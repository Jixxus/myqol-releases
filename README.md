# MyQOL

MyQOL is a native macOS menu bar app with break reminders, window shortcuts, Keep Awake, and Settings for login and updates.

This repository contains public downloads and the signed Sparkle update feed. Application source is maintained separately in a private repository.

## Install and update

Download a ZIP from [Releases](https://github.com/Jixxus/myqol-releases/releases), extract MyQOL, and move it to Applications. Requires macOS 14 or later on Apple Silicon or Intel. Versions before 1.3.0 need a manual installation once to get Sparkle updates.

In MyQOL, open Settings to check for updates or enable automatic update checks. An Update available button appears when a new version is ready. You choose when to install and restart. Update downloads and the feed are verified with Sparkle's Ed25519 signatures.

Current downloads are ad-hoc signed and are not notarized by Apple while the Developer ID certificate is being prepared. macOS may require approval in Privacy & Security. Windows requires Accessibility permission, which may need to be granted again after an update. The bundle ID changed in 1.3.0, so notifications and Launch at login may also need approval once. Existing preferences are retained.

Keep the app in the same location when updating.
