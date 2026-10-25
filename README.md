# Yoink

A small Windows x64 screen recorder that exports animated GIFs.

This repository contains public releases, download links, and release notes.

## Download

Open [Releases](https://github.com/tuncb/yoink-releases/releases) and download
**yoink-windows-x64.zip**. Extract the complete ZIP, then open **Yoink.exe**.
Keep all package files together, including the **tools** folder.

The tested platform is Windows 11 x64. The app requires Windows 10 version 2004
(build 19041) or later. It does not need .NET or a separate Visual C++ runtime.

## Install and update

Open **About & updates** on the first screen. Select **Install** to install the
portable copy. Installed copies show **Update** when a newer release is available.
Yoink checks for updates when this page opens.

If your copy still checks the old **tuncb/yoink** repository, download the new
package manually once. Close Yoink, extract the complete ZIP over the existing
app folder, then open **Yoink.exe**. Settings and saved GIFs are retained.

## Encoder sources and notices

Yoink includes [FFmpeg](https://ffmpeg.org/) under LGPL 2.1 or later. Each release
includes **yoink-ffmpeg-sources.zip** with the matching FFmpeg and zlib sources,
original notices, and build instructions. Keep the license notice beside the
FFmpeg executable.

The ZIP and TAR files that GitHub labels **Source code** contain the files in
this release repository. Use **yoink-ffmpeg-sources.zip** for the encoder sources.
