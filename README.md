# MUSTIFY_MUSIC_PLAYER
# Mustify Music Player

![Mustify Logo](mustify_logo.png)

Mustify is a simple command-line music player built using C++. It allows users to play and manage their music collection directly from the terminal. This README provides an overview of the project, its features, setup instructions, and more.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Usage](#usage)
- [Installation](#installation)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Mustify Music Player is a personal project developed to explore C++ programming and audio playback libraries. It provides a minimalistic yet functional music playing experience within the command-line interface. The project focuses on simplicity and efficiency.

## Features

- **Play Music:** Play audio files in various formats (e.g., MP3, WAV) directly from the command line.
- **Pause and Resume:** Pause and resume playback at any time.
- **Stop Playback:** Stop the currently playing track.
- **Next and Previous:** Navigate between tracks in the playlist.
- **Playlist Management:** Maintain and manage a playlist of favorite tracks.
- **Volume Control:** Adjust the volume of the playback.
- **Shuffle:** Shuffle the order of tracks in the playlist.
- **Looping:** Enable looping of the current track or the entire playlist.

## Usage

1. **Compile:** Compile the source code using a C++ compiler:
   ```
   g++ -o mustify main.cpp audio_player.cpp playlist.cpp -std=c++11
   ```

2. **Run:** Run the compiled executable:
   ```
   ./mustify
   ```

3. **Commands:**
   - `play <file>`: Play a specific audio file.
   - `pause`: Pause the current playback.
   - `resume`: Resume playback.
   - `stop`: Stop the current playback.
   - `next`: Play the next track in the playlist.
   - `prev`: Play the previous track in the playlist.
   - `playlist`: Display the current playlist.
   - `add <file>`: Add a file to the playlist.
   - `remove <index>`: Remove a track from the playlist.
   - `volume <level>`: Set the volume level.
   - `shuffle`: Shuffle the playlist.
   - `loop <mode>`: Set loop mode (`track`, `playlist`, `off`).
   - `help`: Display the list of available commands.

## Installation

Mustify Music Player requires a C++ compiler and a compatible audio playback library, such as the PortAudio library. You can install PortAudio using package managers like `apt` or `brew`. Refer to the PortAudio documentation for installation instructions.

## Configuration

Mustify can be configured by modifying the source code directly. You can customize aspects like default playlist location, audio quality settings, and more.

## Contributing

Contributions to this project are welcome! If you have suggestions, bug fixes, or enhancements, feel free to create a pull request. Please follow the existing code style and guidelines.

## License

This project is licensed under the [MIT License](LICENSE).

---

*Note: Mustify is a personal project created for learning and hobby purposes. It does not aim to compete with professional music player software.*
