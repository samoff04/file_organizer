# File Organizer

## Overview
A simple Python automation tool that organizes files into folders based on their file extensions.

## Features
- Automatically detects file extensions
- Creates folders for different file types
- Moves files into their respective folders
- Handles invalid folder paths
- Supports files without extensions

## Tech Stack
- Python
- os
- shutil

## Project Structure
file_organizer/
├── file_organizer.py
├── README.md
├── requirements.txt
└── .gitignore

## How to Run

### 1. Clone repository
git clone https://github.com/samoff04/file_organizer.git
cd file_organizer

### 2. Run program
python file_organizer.py

### 3. Enter folder path
Provide the folder path when prompted and the files will be organized automatically.

## Example
Before:
Downloads/
photo.jpg
notes.txt
song.mp3

After:
Downloads/
JPG_Files/
TXT_Files/
MP3_Files/

## Requirements
- Python 3.7+

## Future Improvements
- Organize files by categories
- Add GUI or Streamlit interface
- Add summary report
- Handle duplicate filenames
