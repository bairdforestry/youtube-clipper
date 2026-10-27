# YouTube Clipper

**Created by Brandon Baird.**

Download YouTube videos, precise clips or audio, with an optional fix for stereo cancellation that makes voices disappear on mono speakers.

**[Download for Windows (ZIP)](https://github.com/bairdforestry/youtube-clipper/releases/download/v1.1.0-preview.2/YouTube-Clipper-Windows-x64.zip)**

**[Illustrated user guide (PDF)](https://github.com/bairdforestry/youtube-clipper/releases/download/v1.1.0-preview.2/YouTube-Clipper-User-Guide.pdf)**

## Get started

1. Download the ZIP, right-click it and choose **Extract All**.
2. Open the extracted folder and double-click **YouTube Clipper.exe**.
3. Click **Desktop shortcut** inside the app if you want quick access next time.

Keep the entire folder together, including the **runtime** folder. Python, FFmpeg, the YouTube engine, a JavaScript runtime and supporting libraries are included. There are no separate dependency installations or administrator steps.

Paste a link, click **Analyze**, choose a full video or start/end times, choose a format and save folder, then click **Download**. The PDF guide is included in the ZIP and opens from the app's **User guide (PDF)** button.

## Audio repair

Enable **Fix stereo cancellation by using phase-safe dual mono** for recordings whose voices disappear when played on a phone or mono speaker. The fix copies the first channel to both sides. Leave it off for normal stereo. The **Best available - original** audio option keeps the original sound and cannot apply the fix.

## Version and requirements

- **1.1.0 Preview 2**, for 64-bit Windows 10/11.
- Unsigned preview: Windows or an organization's security policy may warn or block launch. Do not disable security settings.
- Internet access and enough disk space are required for downloads.
- Mac packages are not yet available.

This build passed local standalone dependency/startup checks, synthetic audio-cancellation repair, format conversion checks, live YouTube download checks, and extracted-package verification. It has not been qualified on a separate clean Windows 10/11 machine matrix.

Use only for media you have permission to download. Third-party acknowledgments and license files are included in the package.
