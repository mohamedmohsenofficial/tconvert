# 🚀 TConvert - Universal File Converter

![Version](https://img.shields.io/badge/Version-1.0.0-orange?style=for-the-badge)
![Bash](https://img.shields.io/badge/Language-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open_Source-Yes-success?style=for-the-badge)

Introducing **TConvert**, the world’s most private and lightning-fast local file converter. It empowers you to convert absolutely any file type in mere seconds with just 4 keystrokes—100% free, and with no need to install complex, resource-heavy, or bloated software. By running entirely offline directly on your personal machine, TConvert guarantees maximum security and absolute privacy for your data. It’s so secure and reliable, you could comfortably process Obama and Trump's classified work files on it without batting an eye!

**TConvert** is a powerful, interactive, and user-friendly command-line tool designed to convert and compress almost any file type (Videos, Audio, Images, Documents, and E-books). 

Crafted to save time, cure "Terminal Phobia," and make the CLI your best friend!* This script is the ultimate lightweight replacement for heavy GUI software and massive Docker containers.

---

## ⚠️ CRITICAL NOTICE: DEPENDENCIES REQUIRED FIRST
`TConvert` acts as a highly intelligent central commander for your system's existing conversion engines. **Nothing will work if you do not install the required libraries first.** You **MUST** install the following open-source engines on your system before running the tool:
* `ffmpeg` (For Video & Audio processing)
* `imagemagick` (For Image processing)
* `libreoffice` (For Documents & Spreadsheets)
* `calibre` (For E-books)
* `pandoc` (For Text/Markdown files)

**To install all dependencies on Debian/Ubuntu, run:**
```bash
sudo apt update
sudo apt install ffmpeg imagemagick libreoffice calibre pandoc

```

*(You can replace the link below with your actual tutorial GIF/Video link showing the installation process)*


---

## 🏆 Why TConvert? (Comparison)

TConvert replaces gigabytes of heavy tools with a single script. Here is how it compares to other common solutions:

| Feature | 🚀 TConvert (This Tool) | 🐳 Docker Solutions (e.g., Transmute) | 🖥️ GUI Apps (e.g., Handbrake) | ☁️ Online Converters |
| --- | --- | --- | --- | --- |
| **Storage Size** | **~10 KB** | ~5.0 GB | ~100+ MB | 0 MB |
| **Offline Use** | ✅ Yes | ✅ Yes | ✅ Yes | ❌ No |
| **All-in-One Capability** | ✅ Yes (All files) | ✅ Yes (All files) | ❌ No (Media only) | ✅ Yes |
| **Speed & Performance** | ⚡ Native & Fast | 🐢 Containerized overhead | ⚡ Native | 🐌 Depends on internet |
| **Privacy** | 🔒 100% Local | 🔒 100% Local | 🔒 100% Local | ⚠️ Uploads your files |

---

## 📂 Supported Formats

TConvert automatically detects your file type and routes it to the correct engine. Here is what it can handle:

| Category | Supported Formats | Engine Used |
| --- | --- | --- |
| 🎥 **Video** | `mp4`, `mkv`, `avi`, `webm`, `mov`, `flv`, `wmv`, `3gp`, `ts`, `m4v` | `FFmpeg` |
| 🎵 **Audio** | `mp3`, `wav`, `flac`, `m4a`, `aac`, `ogg`, `wma`, `opus` | `FFmpeg` |
| 🖼️ **Images** | `jpg`, `png`, `webp`, `bmp`, `gif`, `tiff`, `ico`, `heic`, `svg` | `ImageMagick` |
| 📄 **Documents** | `docx`, `pdf`, `xlsx`, `csv`, `pptx`, `odt`, `ods`, `html` | `LibreOffice` |
| 📚 **E-books** | `epub`, `mobi`, `azw3`, `pdf`, `fb2` | `Calibre` |
| 📝 **Text** | `md`, `txt`, `rtf` | `Pandoc` |

*(Note: You can type manual extensions outside this list, and TConvert will try its best to process them!)*

---

## ✨ Key Features

* **📊 Real-time Progress Bar:** Watch the conversion progress with a dynamic, real-time percentage bar for media files.
* **🗜️ Smart Compression:** Compress files by a specific percentage (%) or target size (MB).
* **🎨 Beautiful UI:** Red and white themed terminal interface with emojis, blinking indicators, and clean ASCII art.
* **🧠 Auto-Suggestions:** The tool suggests the best formats based on your input file type.

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
2. Choose to **Convert to a new format** or **Compress Only**.
3. Select your target format from a numbered list.
4. Set your desired compression method and level (Optional).
5. Sit back and watch the animated progress bar!

---

## 🤝 Contributing

Open-source project powered by the community! Open Issue or Pull Request for:

* Support for new file formats and conversion engines
* Terminal UI & animation improvements
* Code optimization and speed enhancements
* Cross-platform compatibility improvements

------

## 📜 License & Credits

- **MIT License:** Free to use, modify, and distribute.
- **GitHub:** [@mohamedmohsenofficial](https://github.com/mohamedmohsenofficial)
- **LinkedIn:** [Mohamed Mohsen](https://www.linkedin.com/in/mohamedmohsenofficial)

---

## 🔥 Final Words

Start your **terminal revolution today!** 🎯    
Turn boring terminal commands into a lightning-fast, visually motivating conversion journey!

## 💖 Support

If you enjoy this tool and it saves you time, consider supporting the development! Every contribution keeps the project alive and helps 🌍✨

<a href="https://www.buymeacoffee.com/mohsenofficial" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" >
</a>

<br><br>

<div align="center">
  <b>Created with 💙 by Mohsen</b><br>
  <i>Transforming your terminal, one file at a time.</i><br>
  Love you guys 🤟🏼😘
</div>
