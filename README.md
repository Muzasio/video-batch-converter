# Video Batch Converter Script 🎞️

A Bash script to automate the renaming and ProRes conversion of .mp4/.mkv video files for use in DaVinci Resolve on Linux.

## Features

- ✅ Automatically renames files to `vid1`, `vid2`, etc.
- 🎥 Converts videos to ProRes `.mov` format using `ffmpeg`
- 📺 Shows live conversion progress in terminal
- 💡 Modular functions and optional logging


## Usage

1. Place your `.mp4`/`.mkv` files into a folder.
2. Run the script:

```bash
chmod +x convert_videos.sh
./convert_videos.sh foldername            #If your want to manually run it in terminal
or 
run through nautilus scripts menu right click on desired folder(after making .sh file).
```

### Requirements

Linux (tested on Pop!_OS, but should work on most Debian-based distros)
ffmpeg  – tool for converting multimedia formats 
gnome-terminal  – required if the script opens new terminal windows
