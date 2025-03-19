# Mini Games Chrome Extension

A lightweight Chrome extension featuring a collection of mini-games accessible via a popup interface. This extension includes Tetris, 2048, Minesweeper, and Memory games, designed to be resource-efficient and playable offline after loading.

## Author
- **RihardsL**

## Description
This extension provides a simple and engaging way to play classic mini-games directly in your Chrome browser. The games are built using HTML5, CSS, and JavaScript, with features like progress saving, theme switching (light/dark mode), language support (English, Latvian, Lithuanian, Estonian), and a high score system.

## Features
- **Games**: Tetris, 2048, Minesweeper, and Memory.
- **Offline Support**: Works without an internet connection after initial loading.
- **Themes**: Switch between light and dark modes.
- **Languages**: Supports English, Latvian, Lithuanian, and Estonian.
- **Progress Saving**: High scores are saved locally using Chrome storage.
- **Additional Features**: Timer option (5-minute reminder), difficulty levels, and a Buy Me a Coffee button for support.

## Installation

1. **Clone or Download the Repository**:
   - Download the ZIP file or clone the repository to your local machine:

2. **Load the Extension in Chrome**:
- Open Chrome and navigate to `chrome://extensions/`.
- Enable "Developer mode" in the top right corner.
- Click "Load unpacked" and select the `mini-games-extension` folder.

3. **Verify Installation**:
- The extension icon should appear in your Chrome toolbar. Click it to open the popup and start playing!

## Usage

1. **Open the Popup**:
- Click the extension icon in the Chrome toolbar to open the mini-games interface.

2. **Select a Game**:
- Choose from Tetris, 2048, Minesweeper, or Memory by clicking the respective buttons.

3. **Controls**:
- **Tetris**: Use ←/→ to move, ↓ to speed up, ↑ to rotate.
- **2048**: Use arrows to move tiles.
- **Minesweeper**: Click to reveal cells, avoid mines.
- **Memory**: Click to flip cards and match pairs.

4. **Additional Options**:
- **Theme**: Switch between light and dark modes using the theme dropdown.
- **Language**: Change the language using the language dropdown.
- **Difficulty**: Select easy, medium, or hard (currently a placeholder feature).
- **Timer**: Set a 5-minute timer with the "5 min" button.
- **Scores**: View high scores with the "Scores" button.
- **Support**: Click the "Buy Me a Coffee" button to support the developer.

## Folder Structure:
mini-games-extension/
├── icons/
│   ├── icon16.png
│   ├── icon48.png
│   └── icon128.png
├── styles/
│   └── popup.css
├── scripts/
│   └── popup.js
├── manifest.json
└── popup.html


## Development Notes
- The project uses HTML5, CSS, and JavaScript with no external dependencies.
- All game logic is consolidated in `popup.js` for simplicity.
- The extension requires minimal permissions (only `storage` for saving high scores).
- The `games/` folder was removed as the code is now self-contained in `popup.js`.

## Contributing
If you'd like to contribute, feel free to fork the repository, make improvements, and submit a pull request. Suggestions for new games or features are welcome!

## License
This project is licensed under the MIT License. See the `LICENSE` file for details (if applicable).

## Support
If you enjoy this extension, consider supporting the developer by clicking the "Buy Me a Coffee" button in the popup, which directs to `https://buymeacoffee.com/latvietis`.

---

*Last updated: March 18, 2025*   