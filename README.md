# YouTube Video Downloader (yt-dlp)

A simple Python script to download YouTube videos using [yt-dlp](https://github.com/yt-dlp/yt-dlp).

## Description

This script downloads a YouTube video in the best available quality (video + audio) and saves it as an `.mp4` file in a specified directory.

---

## Requirements

- Python 3.7 or newer
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) library

Install the required library:

```bash
pip install yt-dlp
```

## Usage
```bash
python downloader.py <YouTube-URL> <Output-Directory>
```
```bash
python downloader.py https://www.youtube.com/watch?v=dQw4w9WgXcQ ./downloads
```

Arguments
- {YouTube-URL}: The URL of the YouTube video you want to download.
- {Output-Directory}: The folder where the downloaded video should be saved. If it does not exist, it will be created automatically.

## Notes
- To keep yt-dlp up to date, run:

```bash
pip install -U yt-dlp
```

## License
This script is provided without any specific license. Use it at your own risk.
