<div align="center">
  <img src="Images/Tconvert.png" alt="TConvert Logo" width="250">

# 🎭 TConvert - Universal File Converter
</div>

![Version](https://img.shields.io/badge/Version-2.0.0-orange?style=for-the-badge)
![Bash](https://img.shields.io/badge/Language-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open_Source-Yes-success?style=for-the-badge)

Introducing **TConvert**, the world’s most private and lightning-fast local file converter. It empowers you to convert absolutely any file type in mere seconds with just 4 keystrokes—100% free, and with no need to install complex, resource-heavy, or bloated software. 

By running entirely offline directly on your personal machine, TConvert guarantees maximum security and absolute privacy for your data. It’s so secure and reliable, you could comfortably process Obama and Trump's classified work files on it without batting an eye! 🛡️

---

## 🌟 Why Choose TConvert?
People choose TConvert because it solves the biggest problems with modern converters:
* 🔒 **Absolute Privacy:** Your files never leave your computer. No sketchy online uploads, no data collection.
* 🧠 **No Memorization Needed:** Forget about complex `ffmpeg` or `magick` terminal commands. TConvert asks you simple questions and builds the complex commands under the hood.
* ⚡ **Blazing Fast:** No heavy GUI (Graphical User Interface) draining your RAM or CPU. It communicates directly with your system's core.
* 🪶 **Featherweight:** A ~15 KB script that replaces gigabytes of heavy desktop applications and docker containers.

---

## ⚠️ CRITICAL NOTICE: DEPENDENCIES REQUIRED FIRST
`TConvert` acts as a highly intelligent central commander for your system's existing conversion engines. **Nothing will work if you do not install the required libraries first.** You MUST install the following open-source engines on your system before running the tool:

* `ffmpeg` (For Video & Audio processing)
* `imagemagick` (For Image processing)
* `libreoffice` (For Documents & Spreadsheets)
* `calibre` (For E-books)
* `pandoc` (For Text/Markdown files)
* `python3 & pandas` (For Complex Data formats like JSON, Parquet, etc.)

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

*(Optional: You can also install the Python data dependencies via pip)*

```bash
pip install pandas openpyxl pyarrow lxml

```

---

## 🏆 TConvert vs. The Rest

| Feature | TConvert | Docker Solutions | GUI Apps | Online Converters |
| --- | --- | --- | --- | --- |
| **Storage Size** | **~20 KB** | ~5.0 GB | ~100+ MB | 0 MB |
| **Offline Use** | Yes | Yes | Yes | No |
| **All-in-One Capability** | All files | Yes | No | Yes |
| **Speed & Performance** | Native & Fast | Containerized overhead | Native | Depends on internet |
| **Privacy** | 100% Local | 100% Local | 100% Local | Uploads your files |

---

## 📂 Supported Formats

TConvert automatically detects your file type and routes it to the correct engine. Here is what it can handle:

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

*(Note: You can type manual extensions outside this list, and TConvert will try its best to process them!)*

---

## 🚀 Installation

Once you have installed the dependencies (see top of page), it takes 10 seconds to install TConvert on your Linux/macOS machine:

```bash
# 1. Download the script
wget [https://raw.githubusercontent.com/mohamedmohsenofficial/tconvert/main/tconvert](https://raw.githubusercontent.com/mohamedmohsenofficial/tconvert/main/tconvert)

# 2. Make it executable
chmod +x tconvert

# 3. Move it to your bin folder
sudo mv tconvert /usr/local/bin/

```

---

## 💻 How to Use

Simply open your terminal in any directory and type:

```bash
tconvert

```

**The interactive menu will guide you step-by-step:**

1. Enter your file name (e.g., `video.mp4`).
2. Choose to **Convert** or **Compress**.
3. Select your target format from a numbered list.
4. Set your desired compression method (By % or MB).
5. Sit back and watch the beautiful, real-time progress bar!

---

## 📜 License & Credits

* **MIT License:** Free to use, modify, and distribute.
* **GitHub:** [@mohamedmohsenofficial](https://github.com/mohamedmohsenofficial)
* **LinkedIn:** [Mohamed Mohsen](https://www.linkedin.com/in/mohamedmohsenofficial)

---

## 💖 Support

If you find this project useful, consider supporting its development. Every contribution helps improve features, maintain the project, and keep it accessible for everyone. 🌍✨

<p align="left">
  <a href="https://www.buymeacoffee.com/mohsenofficial" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" width="200">
  </a>
</p>

---

Created by [Mohamed Mohsen](https://www.linkedin.com/in/mohsenofficial)) 💙

Built with passion, curiosity, countless hours of learning, and a deep love for open-source software.

Thank you for using this project and being part of its journey. 🤟🏼😘
