# Application releases

This repository hosts application installers and signed update feeds. It contains no voicemail records or application source code.

## Voicemail Archive for Mac

Installers will appear under Releases after signing, notarization and update testing. No public installer is available yet.

- Installer release tags: `voicemail-archive-vVERSION-BUILD`
- Dedicated Sparkle feed: `https://github.com/sideways-living/releases/releases/download/voicemail-archive-updates/appcast.xml`
- Each installer release includes its ZIP, appcast and SHA256SUMS.txt. The dedicated feed release holds the current validated appcast.

Keep older installer assets available. Other applications must use their own feed tags and must not replace the Voicemail Archive feed. Sparkle applies only to the Mac app; iPhone installation is separate.
