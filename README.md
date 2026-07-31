
<div align="center">
  <img src="Images/Tconvert.png" alt="TConvert Logo" width="2000">

# 🎭 TConvert - Local File Converter
</div>

![Version](https://img.shields.io/badge/Version-2.0.0-orange?style=for-the-badge)
![Bash](https://img.shields.io/badge/Language-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open_Source-Yes-success?style=for-the-badge)

**TConvert** is a fast, offline command-line tool that allows you to convert and compress almost any file type directly on your machine. 

It is completely free, requires no cloud uploads, and keeps your data 100% private. Instead of dealing with complex GUI applications or memorizing long terminal commands, TConvert provides a simple, interactive menu that builds and executes the complex underlying commands for you in seconds.

---

## 🌟 Why Choose TConvert?

* 🔒 **Absolute Privacy:** Your files never leave your local machine. No online uploads, no tracking, no data collection.
* 🧠 **No Memorization Needed:** Forget about complex `ffmpeg` or `magick` flags. TConvert asks you simple questions and handles the heavy lifting under the hood.
* ⚡ **Performance Focused:** No heavy graphical interface draining your RAM or CPU. It communicates directly with your system's core engines.
* 🪶 **Featherweight:** A single lightweight script that replaces gigabytes of heavy desktop applications.

---

## ⚠️ CRITICAL NOTICE: DEPENDENCIES
`TConvert` acts as a central commander for your system's existing conversion engines. **It requires the following open-source engines to be installed on your system to function properly:**

* `ffmpeg` (For Video & Audio)
* `imagemagick` (For Images)
* `libreoffice` (For Documents & Presentations)
* `calibre` (For E-books)
* `pandoc` (For Text/Markdown)
* `python3 & pandas` (For Data formats like JSON, Parquet, CSV)

**Debian/Ubuntu (apt):**
```bash
sudo apt update
sudo apt install ffmpeg imagemagick libreoffice calibre pandoc python3-pandas

```

**Fedora/RHEL (dnf):**

```bash
sudo dnf install ffmpeg ImageMagick libreoffice calibre pandoc python3-pandas python3-openpyxl python3-pyarrow python3-lxml

```

**Arch Linux (pacman):**

```bash
sudo pacman -S ffmpeg imagemagick libreoffice-fresh calibre pandoc python-pandas python-openpyxl python-pyarrow python-lxml

```

*(Optional: Install Python dependencies via pip if not using system packages)*

```bash
pip install pandas openpyxl pyarrow lxml

```

---

## 🏆 TConvert vs. Alternatives

| Feature | TConvert | Docker Solutions | GUI Apps | Online Converters |
| --- | --- | --- | --- | --- |
| **Storage Size** | **~25 KB** | ~5.0 GB | ~100+ MB | 0 MB |
| **Offline Use** | Yes | Yes | Yes | No |
| **Privacy** | 100% Local | 100% Local | 100% Local | Uploads your files |
| **Performance** | Native & Fast | Containerized overhead | Native | Depends on internet |

---

## 📂 Supported Formats

TConvert detects your file type and routes it to the appropriate engine:

| Category | Supported Formats | Engine Used |
| --- | --- | --- |
| 🎥 **Video** | `mp4`, `mkv`, `avi`, `webm`, `mov`, `flv`, `wmv`, `3gp`, `ts`, `m4v` | `FFmpeg` |
| 🎵 **Audio** | `mp3`, `wav`, `flac`, `m4a`, `aac`, `ogg`, `wma`, `opus` | `FFmpeg` |
| 🖼️ **Images** | `jpg`, `png`, `webp`, `bmp`, `gif`, `tiff`, `ico`, `heic`, `svg` | `ImageMagick` |
| 📄 **Documents** | `docx`, `pdf`, `pptx`, `odt`, `odp` | `LibreOffice` |
| 📊 **Data** | `csv`, `tsv`, `json`, `jsonl`, `parquet`, `xlsx`, `xml` | `Python (Pandas)` |
| 📚 **E-books** | `epub`, `mobi`, `azw3`, `pdf`, `fb2` | `Calibre` |
| 📝 **Text** | `md`, `txt`, `rtf` | `Pandoc` |
| 📦 **Archives** | `zip`, `cbz`, `tar`, `tar.gz`, `tar.bz2`, `tar.xz` | `Native Linux (zip/tar)` |

---

## 🚀 Installation & Updating

**Installation:**
Run this single command to download TConvert, make it executable, and move it to your system binaries:

```bash
sudo curl -L "[https://raw.githubusercontent.com/mohamedmohsenofficial/tconvert/main/tconvert](https://raw.githubusercontent.com/mohamedmohsenofficial/tconvert/main/tconvert)" -o /usr/local/bin/tconvert && sudo chmod +x /usr/local/bin/tconvert

```

**Updating:**
TConvert features a built-in auto-updater. Every time you run the script, it checks the repository. If a new version is available, it will automatically download and apply the update for you.

---

## 💻 How to Use

Open your terminal in the folder containing your file and run:

```bash
tconvert

```

**The interactive menu will guide you:**

1. Enter your file name (e.g., `video.mp4`).
2. Choose to **Convert** or **Compress**.
3. Select your target format.
4. Set your desired compression method (By %, or target exact KB/MB/GB).
5. (Optional) Apply advanced settings like muting audio, preserving FPS, or trimming media length.
6. The script processes your file and provides a detailed results summary.

---

## 📜 License & Links

* **License:** [MIT License](https://www.google.com/search?q=LICENSE)
* **GitHub:** [@mohamedmohsenofficial](https://github.com/mohamedmohsenofficial)
* **LinkedIn:** [Mohamed Mohsen](https://www.linkedin.com/in/mohamedmohsenofficial)

---

## 💖 Support

If this tool saves you time or simplifies your workflow, consider supporting its development.

Built for my own needs, shared with the community. Thank you for using TConvert.
