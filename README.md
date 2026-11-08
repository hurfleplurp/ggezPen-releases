# ggezPen

ggezPen is an osu!-inspired rhythm game for Windows, built on the ezPen
drawing engine. Patterns fly toward you through a perspective tunnel. Trace
them with a mouse or drawing tablet, and tap them, as they cross the action
plane in time with the music.

## Downloads

- **[Download ggezPen for Windows](https://github.com/hurfleplurp/ggezPen-releases/releases/latest/download/ggezPen.exe)**
- [Download the command-line chart generator](https://github.com/hurfleplurp/ggezPen-releases/releases/latest/download/ggezPenGenerate.exe)
- [Download the game overview](https://github.com/hurfleplurp/ggezPen-releases/releases/latest/download/GGEZPEN-OVERVIEW.md)
- [Download the executable SHA256 checksums](https://github.com/hurfleplurp/ggezPen-releases/releases/latest/download/SHA256SUMS.txt)
- [Latest release and notes](https://github.com/hurfleplurp/ggezPen-releases/releases/latest)
- [All releases](https://github.com/hurfleplurp/ggezPen-releases/releases)

**Requirements:** 64-bit Windows 10 or 11 and an OpenGL 3.3-capable graphics
driver. Download the executable and run it; you don't need to install a separate
runtime. Mouse and pressure-sensitive drawing tablets are supported. You can import
MP3 or WAV songs from inside the game; charts are generated locally.

**Online leaderboards:** choose a handle and tick **Online** in song select to
automatically submit completed official-track runs to [ezpen.ink](https://ezpen.ink/leaderboard).
No account is required. Score submission is off by default; anonymous server
notices refresh every minute, including update reminders.

Windows may display a reputation warning for a newly downloaded executable.
Only obtain builds from these official releases.

## About this repository

This is the public distribution repository for ggezPen, not its source repository.
Builds and documentation are attached to GitHub Releases.

The download links above always point to assets on the latest stable release.
GitHub redirects these links to the current version, so a website can use them
directly. Version-specific links remain available on each release page.

## Publishing updates

Releases are produced by `release-ggezpen.ps1 -Version x.y.z -Publish` in the
source repository. It builds, tests, uploads to a draft, verifies the uploaded
digests, then publishes the release as the latest stable release. Keep these
filenames unchanged so links continue to work:

- `ggezPen.exe`
- `ggezPenGenerate.exe`
- `GGEZPEN-OVERVIEW.md`
- `SHA256SUMS.txt` (SHA256 of both executables)
