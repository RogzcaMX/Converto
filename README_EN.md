<p align="center">
  <a href="./README.md">
    <img src="https://img.shields.io/badge/🌐_Leer_en_Español-2563eb?style=for-the-badge" alt="Leer en Español" height="35" />
  </a>
</p>

<h1 align="center">⚡ Converto 2.0 "Filanan"</h1>

<p align="center">
  <strong>Your unified desktop hub to convert, compress, merge, and optimize multimedia files and documents 100% offline.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0.0_«Filanan»-blue?style=flat-square" alt="Version" />
  <img src="https://img.shields.io/badge/Tauri-v2-24C8D8?style=flat-square&logo=tauri&logoColor=white" alt="Tauri v2" />
  <img src="https://img.shields.io/badge/Svelte-Kit-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="SvelteKit" />
  <img src="https://img.shields.io/badge/Rust-Backend-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Engines-FFmpeg_%7C_ImageMagick-red?style=flat-square" alt="Engines" />
  <img src="https://img.shields.io/badge/Platform-Windows_x64-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows" />
  <img src="https://img.shields.io/badge/Languages-19_(RTL_Supported)-10b981?style=flat-square" alt="19 Languages" />
</p>

---

## 📖 Overview

**Converto 2.0 "Filanan"** is an all-in-one desktop application for Windows, completely rebuilt from the ground up following its original Python release. Powered by a modern native architecture (**Rust + Tauri v2 + Svelte**), it delivers dramatically faster, smoother, and more reliable performance with a brand-new interface tailored for both everyday users and heavy workflows (media editing, comic/manga *scanlation*, document processing, and bulk file organization).

No internet connection or external dependencies are required: all processing runs locally on your machine with **FFmpeg** and **ImageMagick** bundled directly inside the application.

---

## ✨ Key Features

### 🛠️ 5 Specialized Processing Engines

* **🖼️ Images & Comic/Album Builder:**
  * **Ultra-fast parallel processing:** Batch-convert across 5 concurrent lanes (`JPG`, `PNG`, `WEBP`, `AVIF`, `HEIC`, `BMP`, `TIFF`, multi-layer `256×256` `ICO`, `PSD`, `EPS`).
  * **Comic & Album Bundler:** Package folders or image sequences directly into **CBZ Comics (`.cbz`)**, **CBT (`.cbt`)**, **EPUB Comics (`.epub`)**, **Multi-page TIFF (`.tiff`)**, and **Animated GIF (`.gif`)** with dedicated quality controls.
  * Resizable thumbnail previews and multi-selection inside the queue.

* **🎵 Audio & Track Merging:**
  * Batch transcode between `MP3`, `WAV`, `FLAC`, `M4A`, `OGG`, `OPUS`, `AMR`, and more.
  * **Extract audio from video:** Drop any video file to extract its audio track immediately.
  * **Unify Audio Mode:** Merge multiple songs, voice notes, or video tracks sequentially into a single continuous audio file.
  * Fine-grained control over **Bitrate** (with automatic *Lossless* format detection), **Sample Rate** (dynamically adjusted per codec), and **Channels** (*Stereo* / *Mono*).

* **🎬 Video & GIF Export:**
  * Smooth transcoding across `MP4`, `MKV`, `AVI`, `MOV`, `WEBM`, `FLV`, `WMV`, plus direct **Animated GIF export**.
  * Ready-to-use compression presets (*High Quality*, *Balanced*, *Compressed*, *Ultra Light*) and resolution scaling (including `360p` for mobile devices).

* **📄 Documents, Code & PDFs:**
  * **Documents to PDF:** Auto-detect and convert `.DOCX`, `.TXT`, images, and source code/script files (`.PY`, `.JS`, `.RS`, etc.) into individual PDFs or a single merged document.
  * **PDF Tools:** Merge multiple PDFs into one, extract all text into `.TXT`, or render PDF pages into images (`PNG`, `JPG`, `WEBP`) with exact **DPI** control (`72`, `150`, `300`, or `600 DPI`).
  * **Unify Texts:** Consolidate multiple plain text or code files into a single document.

* **📦 Compression & Extraction:**
  * Archive files and full folders with selectable compression levels (*Store Only / Fast / Normal / Maximum Ultra*) or uncompressed `TAR`.
  * Batch-extract `.ZIP`, `.RAR`, `.7Z`, `.TAR`, `.TAR.GZ`, `.TAR.BZ2`, and `.TAR.XZ` archives while keeping original names or setting custom output folder names.

---

### 🖥️ User Experience & Productivity

* **📊 Live Status Monitor:** Track total items in queue, pending, active, and completed counts, overall batch progress bar, currently processing file, and a persistent task history with one-click access to the destination folder.
* **📍 Dynamic Multi-Path Export:** Process files dragged from multiple folders simultaneously and save each output right alongside its source file, inside default Windows libraries, or into organized subfolders.
* **🏷️ Renaming Rules & Overwrite Protection:** Add custom prefixes, suffixes, or batch filenames. When a file already exists at the destination, choose between overwriting it or continuing with automatic sequential numbering (`01`, `02`...).
* **🌓 Visual & Audio Customization:** Collapsible and resizable sidebar, Light and Dark themes (manual, synced with Windows, or automatically scheduled by time), custom success/error sound alerts, and automatic File Explorer launch upon completion.
* **🌍 Global Support for 19 Languages (including RTL):** Spanish, English, Portuguese, French, German, Italian, Russian, Japanese, Chinese (Simplified & Traditional), Korean, Hindi, Turkish, Polish, Dutch, Ukrainian, Indonesian, Vietnamese, and **Arabic** (with full Right-To-Left layout mirroring).

---

## 🚀 Download & Installation

Head over to the **[Releases](https://github.com/RogzcaMX/Converto/releases)** section of this repository and download your preferred edition for **Windows (64-bit)**:

1. **Standard Installer (Recommended):**
   * Download `Converto.v2.0.0.x64.setup.exe` and run it. Includes the offline WebView2 runtime and required libraries to work out of the box without internet.
2. **Portable Edition (No installation required):**
   * Download `Converto.v2.0.0.x64.Portable.zip`, extract all contents into a folder, and launch `Converto.exe`. Includes FFmpeg and ImageMagick ready to use.

---

## ☕ Support the Project

If **Converto** helps save time in your daily workflow, consider supporting its ongoing maintenance and future updates:

* **PayPal:** [Donate via PayPal](https://www.paypal.com) *(replace with your link)*
* **Ko-Fi:** [Donate on Ko-Fi](https://ko-fi.com) *(replace with your link)*
