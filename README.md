# ShiftWheel for Windows: downloads

This repository only holds the ShiftWheel installers, published as [releases](../../releases). The app's own code
isn't here: ShiftWheel is proprietary software, used under its terms of service.

**Download:** [ShiftWheel-Setup.exe](../../releases/latest/download/ShiftWheel-Setup.exe), the latest version, for
Windows 10 (1809 or later) and Windows 11, 64-bit. Each release lists the installer's SHA-256 checksum.

## Third-party software
ShiftWheel includes open-source software under its own licences:

- **FFmpeg** (the "essentials" build by [gyan.dev](https://www.gyan.dev/ffmpeg/builds/)), licensed under the
  [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html). ShiftWheel runs it as a separate program
  (`tools\ffmpeg.exe`), and installs its licence beside it (`tools\FFMPEG-LICENSE.txt`). Each release names the
  FFmpeg version it includes and where its source code is.
- whisper.cpp and the Whisper base model (MIT), rembg's "silueta" model (MIT; based on U²-Net, Apache 2.0),
  ONNX Runtime (MIT), PDFsharp (MIT), PdfPig (Apache 2.0), QRCoder (MIT) and .NET (MIT).
