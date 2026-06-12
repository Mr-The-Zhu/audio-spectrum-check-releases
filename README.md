# MP3 Spectrum Check — downloads

A Windows tool that inspects MP3 and FLAC files by their spectrum to spot fakes —
MP3s passed off as 320 kbps (but actually upsampled from a lower bitrate) and
"fake" FLAC files transcoded from a lossy source. Includes a built-in
spectrogram viewer (Spek-style).

## Download

Get the latest build from the **[Releases](../../releases/latest)** page.
Download `MP3SpectrumCheck-Setup.exe` and run it.

## Install

1. Run `MP3SpectrumCheck-Setup.exe` and allow administrator privileges.
2. **Nothing else is required** on the target machine — no Python, no ffmpeg;
   everything is bundled inside.
3. After installing: right-click an MP3/FLAC file or a folder →
   **"MP3 Spectrum Check"**. On Windows 11, first choose
   "Show more options" (or Shift+Right-click).

Uninstall via Windows "Apps & features".

## Note

The method is not 100% accurate: vintage recordings and some studio masters can
also have a rolled-off top end. Treat a suspicious result as a reason for manual
review (open the spectrogram), not as a verdict.

---

The source code lives in a separate private repository. This repository exists
only to distribute the ready-made builds.
