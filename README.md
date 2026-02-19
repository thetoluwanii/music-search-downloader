# music-search-downloader
Overview

A desktop-based Python application that allows users to extract and download audio from online video sources. The application integrates external libraries for media extraction and audio processing while providing a user-friendly graphical interface.
Problem Statement

Downloading and converting online video content into audio typically requires command-line tools or multiple applications. This project simplifies the workflow into a single GUI-based application.

Features

1. URL-based audio extraction

2. Automatic audio conversion

3. Local file saving

4. Download history storage (JSON-based)

5. Structured error handling

6. GUI interaction

## Tech Stack

- Python

- yt-dlp

- pydub

- CustomTkinter

- JSON

## System Architecture

User Input (URL)
→ yt-dlp extracts media
→ Audio processed via pydub
→ File saved locally
→ Download history updated

## Key Technical Concepts Demonstrated

External library integration

File handling & directory management

JSON data storage

GUI design & event-driven logic

Debugging and runtime error resolution


# Challenges & Solutions

Issue: Dependency conflicts during audio conversion
Solution: Structured dependency management and validation checks before execution

# Lessons Learned

Managing third-party libraries

Designing modular code structure

Improving usability through structured feedback
