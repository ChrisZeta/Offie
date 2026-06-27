# Offie

Download YouTube audio and video at the highest quality, straight from your Mac.

Offie is a native SwiftUI app for macOS — fast, lightweight, self-contained, and available in Italian and English.

* **Website:** [offie.chriszeta.it](https://offie.chriszeta.it)
* **Platform:** macOS 14.0 (Sonoma) or later
* **Architecture:** Universal (Apple Silicon & Intel)
* **Languages:** Italian and English (instant hot-swap)

---

## 📥 Download

Get the latest version from the [**Releases**](../../releases) page.

---

## ✨ Features

* **🎵 Audio Downloads** — Choose between `M4A`, `M4A Max`, `OPUS`, `MP3`, `MP3 320k`, `FLAC`, and `WAV`. Metadata and high-quality cover art are embedded automatically.
* **🎬 Video Downloads** — Download in resolutions from `360p` up to `4K (2160p)`, automatically merged with audio into a single `MP4` file.
* **🔎 Built-in Search** — Search YouTube directly within the app without needing a YouTube API key, or just paste a link.
* **📥 Queue Management** — Run up to 5 parallel downloads, monitor progress with real-time speed/ETA, and inspect per-item logs.
* **✂️ Smart Splitter** — Divide audio or video files into parts of `N` minutes while preserving metadata and cover art in every slice.
* **👑 Premium Formats (Optional)** — Authenticate with your Firefox YouTube cookies to access high-bitrate Premium streams.
* **🌍 Bilingual Interface** — English and Italian interface with instant hot-swapping, no app restart required.
* **⚡ Self-Contained** — Comes bundled with universal builds of `yt-dlp` and `ffmpeg`. Zero external dependencies or Homebrew installation required (but Homebrew is supported for extra speed).

---

## 💻 Requirements

* macOS 14.0 (Sonoma) or later
* Apple Silicon (M1/M2/M3/M4) or Intel processor (Universal Binary)

---

## 🚀 Installation

1. Download **`Offie.dmg`** from the [Latest Releases](../../releases) section.
2. Open the DMG and drag **Offie.app** to your `/Applications` folder.

> [!IMPORTANT]  
> **Offie is not notarized by Apple.**  
> On the very first launch, macOS Gatekeeper will block it from running.  
> To open it: **Right-click (or Control-click) Offie.app → select Open → click Open** in the dialog box, or go to **System Settings → Privacy & Security → scroll down and click Open Anyway**.

---

## 🔄 Updates

Offie features automatic, secure in-app updates powered by **Sparkle 2**:
* When a new version is released, the app will notify you with release notes.
* Updates are downloaded, cryptographically verified using **Ed25519 signatures**, installed, and the app is relaunched automatically.
* Since updates are cryptographically signed by the developer, **you only need to perform the initial Gatekeeper bypass once during the first install**. Future updates will launch instantly.

---

## ⚖️ Legal

Offie is an independent project and is not affiliated with, authorized, or endorsed by YouTube or Google.

* Respect copyright laws. Download only content you have the right to download under YouTube's Terms of Service.
* `yt-dlp` and `ffmpeg` are open-source tools distributed under their respective licenses (Unlicense and LGPL-2.1).
