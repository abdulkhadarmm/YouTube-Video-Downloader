# 🎥 YouTube Video Downloader (GUI)

A simple Python GUI application to download and merge YouTube videos in your selected quality (e.g., 360p, 720p, 1080p) using `yt-dlp` and `ffmpeg`.

---

## 🚀 Features

- User-friendly GUI to enter YouTube URL.
- Fetch and display available video/audio formats.
- Easily choose quality like 360p, 720p, 1080p.
- Downloads video and audio separately, then merges them automatically.
- Shows live download progress and logs during execution.

---

## 🧰 Requirements

### 📦 For Windows (Recommended via [Scoop](https://scoop.sh))

Install Scoop first (if not already installed):

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
irm get.scoop.sh | iex
```

Then install the required tools:

```powershell
scoop install python
scoop install yt-dlp
scoop install ffmpeg
```

✅ Make sure the scoop\shims path is in your system environment variables so Python and yt-dlp are globally accessible.

### 💻 For macOS/Linux
#### macOS (via Homebrew):

```bash
brew install python
brew install ffmpeg
brew install yt-dlp
```

###Ubuntu/Debian:

```bash
sudo apt update
sudo apt install python3 python3-pip ffmpeg -y
pip3 install yt-dlp
```

## 📂 How to Run

1. Clone this repo or download the `Youtube-Video-Downloader.py` script.
2. Open terminal or PowerShell and navigate to the project directory.
3. Run the application:

```bash
git clone https://github.com/abdulkhadarmm/YouTube-Video-Downloader.git
cd YouTube-Video-Downloader
python Youtube-Video-Downloader.py
```
If you're on Linux/macOS, you might need to use python3 instead:
```bash
python3 Youtube-Video-Downloader.py
```

## 🔐 Permissions Note
On first-time Scoop install, you may need to run:

```bash
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```
If you see command not found errors, make sure Scoop's `shims` directory is added to your PATH.

## 🖼️ Screenshot

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
