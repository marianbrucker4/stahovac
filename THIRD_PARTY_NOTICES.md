# Oznámenia o súčastiach tretích strán · Third-party notices

Sťahovač obsahuje nasledujúce programy a písma tretích strán. Každá súčasť má vlastnú licenciu.
*Sťahovač bundles the following third-party programs and fonts. Each is under its own license.*

## FFmpeg 7.1 (`Contents/Resources/bin/ffmpeg`, `ffprobe`)
- Licencia / License: **GNU General Public License v2 or later (GPL-2.0+)** – zostavenie s `--enable-gpl`, `--enable-libx264`, `--enable-libx265`, `--enable-libmp3lame`, `--enable-libopus`, `--enable-libvmaf`, `--enable-libopenjpeg`.
- Zdrojový kód FFmpeg 7.1 / Source code: <https://ffmpeg.org/releases/ffmpeg-7.1.tar.xz> (projekt: <https://ffmpeg.org/>)
- x264: <https://www.videolan.org/developers/x264.html> · x265: <https://bitbucket.org/multicoreware/x265_git>
- Text licencie GPL-2.0 / License text: <https://www.gnu.org/licenses/old-licenses/gpl-2.0.html>
- Binárky FFmpeg boli prevzaté ako hotové zostavenie pre macOS arm64 a nie sú nijako upravené. Presný konfiguračný reťazec zobrazí príkaz `ffmpeg -version`.
  The FFmpeg binaries are an unmodified prebuilt macOS arm64 build; the exact configuration is printed by `ffmpeg -version`.
- Na požiadanie vám sprístupníme zdrojový kód zodpovedajúci tomuto zostaveniu: otvorte issue v tomto repozitári.
  Upon request we will provide the corresponding source for this build: open an issue in this repository.

## yt-dlp (`Contents/Resources/yt-dlp-dist/`)
- Licencia / License: **The Unlicense** (public domain); balík obsahuje aj knižnice s vlastnými licenciami, pozri `yt-dlp-dist/_internal/THIRD_PARTY_LICENSES.txt`.
- Projekt / Project: <https://github.com/yt-dlp/yt-dlp>

## Mulish (písmo / font)
- Licencia / License: **SIL Open Font License 1.1** – súbor `Contents/Resources/fonts/Mulish-OFL.txt`
- Projekt / Project: <https://github.com/googlefonts/mulish>

## Python (systémový interpret)
Sťahovač spúšťa lokálny server cez systémový `/usr/bin/python3` (súčasť macOS / Xcode Command Line Tools). Nie je súčasťou balíka.
