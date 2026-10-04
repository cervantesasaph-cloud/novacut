# NovaCut

A small, standalone video editor for Windows 10/11 x64. NovaCut 2.1 is about **1.9 MiB** and includes its rendering engine in one executable.

## Download and run

1. Download [NovaCut.exe](NovaCut.exe) from this repository using GitHub's **Download raw file** button.
2. Double-click the downloaded executable.

No installer, BAT file, Python installation, or separate compiler is needed to use the app. The embedded engine uses temporary disk space while running.

## Edit a video

1. Import your video clips.
2. Select a clip in the left panel and set its trim points in the right panel.
3. Arrange clips in the order you want. Use split or duplicate when needed.
4. Adjust effects, volume, rotation, mirror, and fades.
5. Seek with the playhead or use **Play 20s** to render a short preview.
6. Choose export resolution, frame rate, speed, and quality, then export an MP4.

Save a `.ncut` project to continue editing later. Projects reference the original videos; keep those files available at their saved locations.

## Features

- Up to 64 clips, trimming, reordering, splitting, and duplication
- 24-step undo and redo
- In-app rendered previews and playhead seeking
- Mute and volume gain from 0% to 200%
- Grayscale, vivid, and invert effects
- Rotation and mirror controls
- Video and audio fades
- PNG snapshots
- MP4 export using H.264 video and AAC audio
- 480p, 720p, 1080p, 1440p, and 4K output
- 24, 30, or 60 FPS; 0.5x, 1x, or 2x speed
- Smaller, balanced, and high-quality export settings
- Version 1 and 2 project support

## Source and licenses

Download [NovaCut-source.zip](NovaCut-source.zip) for the application source, build configuration, validation scripts, and bundled engine sources. See `README-source.txt` inside for developer build instructions.

The NovaCut application source uses the MIT license. Its bundled FFmpeg/x264 engine includes GPL-licensed components; zlib has its own license, and the bundled LZMA SDK code is public domain. See the source archive and bundled notices for the applicable terms. The MIT license does not replace these third-party licenses.

## Validation and feedback

Export pipeline checks, resource integrity checks, compilation, and layout geometry checks passed. The Windows GUI itself has not yet been run in the build environment; a Windows smoke test is still needed.

To report a problem, open an issue with your Windows version, the steps that caused it, any error message, and the input video's format. Do not include private videos or personal information.
