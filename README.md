# WatchdogFileOrganizer
A project for organizing files according to their category of folders like video, audio , document etc

# File Organizer

File Organizer is a Python script that automatically organizes files in a specified directory based on their types. It monitors the directory for file system changes and categorizes files into separate folders for audio, video, images, and documents.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Configuration](#configuration)
- [Supported File Types](#supported-file-types)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [License](#license)

## Features

- Automated organization of files into distinct folders.
- Monitors the specified directory for changes using the `watchdog` library.
- Supports various file types, including audio, video, images, and documents.

## Usage

1. Set up the source and destination directories in the script (`file_organizer.py`).
2. Run the script using Python:

    ```bash
    python file_organizer.py
    ```

3. The script will continuously monitor the specified source directory for changes and organize files accordingly.

## Configuration

- **Source Directory (`source_dir`):** The directory to be monitored for file changes.
- **Destination Directories (`dest_dir_sfx`, `dest_dir_music`, etc.):** Folders where files will be categorized based on their types.

## Supported File Types

- **Audio:** `.m4a`, `.flac`, `.mp3`, `.wav`, `.wma`, `.aac`
- **Video:** `.webm`, `.mpg`, `.mp4`, `.avi`, `.wmv`, `.mov`, and more.
- **Images:** `.jpg`, `.png`, `.gif`, `.bmp`, `.svg`, and more.
- **Documents:** `.doc`, `.docx`, `.pdf`, `.xls`, `.xlsx`, `.ppt`, `.pptx`, and more.

## Dependencies

- [watchdog](https://pypi.org/project/watchdog/): A Python library for monitoring file system events.

## Installation

1. Install the required dependencies:

    ```bash
    pip install watchdog
    ```

2. Set up the script with the appropriate source and destination directories.

3. Run the script as described in the [Usage](#usage) section.

## License

This project is licensed under the [MIT License](LICENSE).
