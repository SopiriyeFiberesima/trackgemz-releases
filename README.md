# TrackGemz downloads

**[trackgemz.com](https://trackgemz.com)** · a music library suite for DJs on macOS.

TrackGemz fills in missing genres and years, repairs blank artist names, clears
junk tags, embeds artwork, finds duplicates, spots upscaled files pretending to
be 320 kbps, and exports a clean set to USB. It runs locally and works alongside
Serato, rekordbox, Engine DJ, Traktor, VirtualDJ and djay.

This repository holds the downloads and the auto-update manifests. The app
itself is not developed here.

## Download

**[Get the latest release →](https://github.com/SopiriyeFiberesima/trackgemz-releases/releases/latest)**

Pick the build that matches your Mac:

| Your Mac | Download |
|---|---|
| Apple Silicon (M1, M2, M3, M4) | `TrackGemz_aarch64.dmg` |
| Intel | `TrackGemz_x86_64.dmg` |

Not sure which you have? Apple menu → **About This Mac**. If the Chip line says
Apple M-something, take the Apple Silicon build. If it says Intel, take the
Intel one.

Open the .dmg and drag TrackGemz to Applications. Both builds are signed and
notarized by Apple, so no security warnings to click through.

## Updates

The app updates itself. `latest.json` in each release is the manifest the
built-in updater reads, and the `.app.tar.gz` and `.sig` files are what it
downloads and verifies. You do not need to come back here after installing.

## Requirements

macOS, Apple Silicon or Intel. Scanning and browsing your library is free.
Changing files is a paid feature, and the pricing is on
[trackgemz.com](https://trackgemz.com).

## Help and community

- **Website and FAQ** · [trackgemz.com](https://trackgemz.com)
- **Report a problem or ask a question** · open an issue on this repository
