# Wardeye releases

Signed and notarized builds of the Wardeye macOS app. Source code is private; this repository only hosts release files.

**Download:** [latest Wardeye.dmg](https://github.com/jugb6050/wardeye-releases/releases/latest/download/Wardeye.dmg) · [all releases](https://github.com/jugb6050/wardeye-releases/releases)

- Requires macOS 14 or later (Apple Silicon or Intel).
- Signed with Developer ID (team 5JM832292H) and notarized by Apple. Each release lists the SHA-256 of its DMG.
- Wardeye is in early testing. It watches for calls and does not record or store call audio or video.

Check a download:

```sh
shasum -a 256 ~/Downloads/Wardeye-*.dmg
spctl --assess --type open --context context:primary-signature -v ~/Downloads/Wardeye-*.dmg
```
