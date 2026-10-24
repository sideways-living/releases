# pobox.watch for Mac

This directory hosts the signed Sparkle update feed and immutable notarised
install archives for the independently distributed pobox.watch macOS app.

- Sparkle feed: `https://raw.githubusercontent.com/sideways-living/releases/main/pobox.watch/appcast.xml`
- Install archives and checksums: `pobox.watch/releases/`
- Minimum system version: macOS 14

Every archive filename includes both the marketing version and build number.
Published files must not be replaced. Release a new build number when the app
changes so Sparkle can compare and validate updates safely.

The Sparkle private signing key and Apple notarisation credentials are not
stored in this repository.
