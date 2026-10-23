# Recording Compressor

### By Web Emporium

A local Windows app for shrinking screen recordings to a chosen file-size limit. Built for bug reports, demos and other recordings that need to fit an upload cap.

## Download and run

This is an **unsigned Windows x64 beta**, intended for testing on Windows 10/11. Comprehensive Windows compatibility, antivirus and performance testing is still pending.

1. Open this repository's **Releases** page.
2. Download **Web-Emporium-Recording-Compressor-0.2.0-win-x64.zip** from the release assets. GitHub's automatically generated **Source code** downloads are not the app.
3. Use **Extract All** and open **Recording Compressor.exe** in the extracted folder. Keep all files and folders together. Python and FFmpeg are included; no separate installation is required.

The ZIP is about 224 MB and extracts to about 505 MB. Allow additional disk space for your recording and temporary export files. If Windows security blocks it, stop and report the warning. Do not disable Windows protection.

## Try one recording

1. Choose a non-sensitive recording from your computer.
2. Select **10, 25, 100 MB or Custom**. MB means 1,000,000 bytes.
3. Keep or lower the resolution and frame rate; keep or remove audio.
4. Choose a new MP4 destination and compress.
5. Compare a matching still frame, then play the saved MP4 to check small text, motion and sound.

## What it does

- Local processing, without an account, uploads or telemetry.
- H.264 MP4 output with optional AAC audio.
- Original / 1080p / 720p resolution and original / 30 / 15 fps controls.
- Before-and-after still-frame comparison, including a native-pixel center crop.
- Checks successful exports against the selected byte limit. Uses a new output file rather than replacing the original.

## Beta limits

Compression is lossy: original resolution does not guarantee unchanged detail. Very tight limits can fail or make text unreadable. Input compatibility depends on the included codecs; common MP4, MOV, MKV, WebM and AVI recordings are supported, not every file in those containers. HDR and sources above 240 fps are rejected.

One recording at a time. No batch queue, trimming, in-app playback or automatic updates. A forced crash may leave temporary export files. Keep your originals.

## Feedback

Report your Windows version, input format and size, chosen limit, output size, readability, audio sync and any error. Do not attach private recordings, customer data or screenshots containing secrets to public reports.

## Notices

This repository hosts release information, not the full development project. See [NOTICE.md](NOTICE.md) and the licenses included with the app. Keep the bundled third-party notices and corresponding media-runtime source archive with the distribution.
