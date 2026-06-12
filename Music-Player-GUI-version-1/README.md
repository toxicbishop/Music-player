# Music Player GUI Version 1

This is the initial graphical user interface for the Music-with-python project.

## Features
- Modern UI using `customtkinter`
- Play, Pause, Resume, and Stop functionality
- File selection for MP3 and WAV files
- Audio playback powered by `pygame`

## Requirements
- Python 3.x
- `customtkinter`
- `pygame`

## How to Run (Source Code)
```bash
python app.py
```

## Running the Standalone Desktop App
You can run this application without installing Python or any dependencies using the pre-compiled executable:
1. Navigate to the `dist/` directory (or download `MusicPlayer-v1.exe`).
2. Run `MusicPlayer-v1.exe` directly on Windows.

## Building the Desktop App from Source
If you want to package the app yourself, make sure PyInstaller is installed (`pip install pyinstaller`) and run:
```bash
pyinstaller --noconsole --onefile --name "MusicPlayer-v1" app.py
```
This will compile the app and place the output executable inside the `dist/` directory.
