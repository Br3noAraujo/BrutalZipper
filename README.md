<p align="center">
  <img src="https://i.imgur.com/Hc5vQOC.png" alt="BrutalZipper Banner"/>
</p>

<h1 align="center">☠️ <span style="letter-spacing: 2px;">BrutalZipper</span> ☠️</h1>

<p align="center">
  <b><i>The Reaper of Compression</i></b><br>
  <span style="color: #888;">Maximum efficiency for real-world files and folders.<br>No mercy. No loss. Only bones remain.</span>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg"/>
  <img src="https://img.shields.io/badge/Python-3.8%2B-informational"/>
  <img src="https://img.shields.io/badge/Ultra_Mode-Enabled-red?logo=skull"/>
</p>

<hr style="border: 1px solid #222;"/>

<pre align="center"><b>"Your files won't feel a thing..."</b></pre>

---

## 💀 Features

- ⚡ <b>Ultra-fast & ultra-efficient</b> compression and decompression
- 🗂️ Compresses files or entire directories (with tar + zstd)
- 🧠 Smart output naming and error handling
- 🧵 Multi-threaded (uses all your CPU power)
- 🎨 CLI with progress bar and colored output
- 🦴 Cross-platform: Linux, macOS, Windows
- ☠️ <b>ULTRA MODE</b>: Pushes your hardware to the limit for maximum compression

<details>
<summary>🔎 <b>How does it work?</b></summary>
<br>
BrutalZipper uses <b>zstandard (zstd)</b> for state-of-the-art compression, and wraps directories in a <b>tar</b> archive before compressing. The result: maximum compatibility and efficiency, with no data loss.
</details>

---

## ⚰️ Installation

```bash
pip install -r requirements.txt
```

---

## ⚡ Usage

```bash
python3 brutalzipper.py -c <input> [output] [options]   # Compress
python3 brutalzipper.py -d <input> [output]             # Decompress
```

### Main Options

| Option         | Description                                 |
| -------------- | ------------------------------------------- |
| `-c`           | Compress file or directory                  |
| `-d`           | Decompress .zst or .tar.zst                 |
| `-o`           | Output file or directory (optional)         |
| `-L`           | Compression level (1-22, default: 3)        |
| `--ultra`      | ☠️ Activate ULTRA MODE (max compression)    |
| `-l`           | Enable logging to brutalzipper.log          |
| `-h`           | Show help                                   |

---

## 🪦 Example

```bash
# Compress a folder with default settings
python3 brutalzipper.py -c myfolder

# Compress a file with custom output
python3 brutalzipper.py -c myfile.txt myfile.txt.zst

# Decompress
python3 brutalzipper.py -d archive.tar.zst

# ☠️ ULTRA MODE: Maximum compression, all CPU threads
python3 brutalzipper.py -c myfolder --ultra
```

---

## ☠️ ULTRA MODE: The Reaper's Embrace

<p align="center">
  <img src="https://i.imgur.com/D7ONGvN.png" alt="ULTRA MODE" width="500"/>
</p>

<blockquote align="center">
  <b>"When you want the smallest file, no matter the cost...<br>
  The Reaper will squeeze every byte from your data."</b>
</blockquote>

> **Warning:** ULTRA MODE uses the highest compression level and all CPU threads. It will be slow and RAM-hungry, but will squeeze every byte possible. Use only if you want the absolute smallest file, no matter the cost!

---

## ⚰️ Output Examples

| Input           | Output                |
| --------------  | ---------------------|
| `myfolder`      | `myfolder.tar.zst`    |
| `myfile.txt`    | `myfile.txt.zst`      |
| `archive.tar.zst` | `archive/` (auto-extracted) |

---

## 🦴 License & Credits

<p align="center">
  <img src="https://em-content.zobj.net/source/microsoft-teams/363/skull_1f480.png" width="32"/>
</p>

<p align="center">
  <b>MIT License</b><br>
  Open source. Coded by <a href="https://github.com/Br3noAraujo">Br3noAraujo</a>.<br>
  <i>Let the Reaper handle your files...</i>
</p> 