# LinkedIn Voice Assistant Chrome Extension

A simple voice assistant Chrome extension to enhance the LinkedIn user experience by providing voice command functionalities.

## Overview

The LinkedIn Voice Assistant is a Chrome extension designed to offer a hands-free browsing experience on LinkedIn. With voice commands and a convenient keyboard shortcut, users can effortlessly access their saved posts on LinkedIn.

## Features

- **Open Saved Posts**: Use voice commands to open your saved posts on LinkedIn.
- **Voice Command Support**: Interact with the extension using voice commands.
- **Keyboard Shortcut**: Use the keyboard shortcut `Shift + Alt + O` to trigger the extension.

## Installation

### From Source Code

#### Prerequisites

- [Git](https://git-scm.com/)
- [Google Chrome Browser](https://www.google.com/chrome/)

#### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/tejas-2104/chrome-extension.git
    ```

2. Open Google Chrome and go to `chrome://extensions/`.

3. Enable `Developer mode` by toggling the switch in the top-right corner.

4. Click on the `Load unpacked` button and select the directory where you cloned the repository.

5. Once loaded, the extension will appear in the Chrome toolbar as the LinkedIn Voice Assistant icon ![Extension Icon](images/icon-16.png).

## Usage

### How to Use the Extension

1. **Voice Command**:
    - Say "Open post" to open your saved posts on LinkedIn.
    
2. **Keyboard Shortcut**:
    - Press `Shift + Alt + O` to trigger the extension and open your saved posts on LinkedIn.

### Troubleshooting

- If the extension is not working or the popup is not displaying:
    1. Make sure the extension is enabled in `chrome://extensions/`.
    2. Refresh the LinkedIn page or reload the extension.

## Development

### Project Structure

- `manifest.json`: Contains metadata and configuration for the Chrome extension.
- `scripts/content.js`: Contains the main logic to add the "Saved Posts" button to LinkedIn's navigation bar and implement the voice command functionality.
- `scripts/popup.js`: Contains logic to close the popup after a certain time.
- `images/`: Contains the icon images for the extension.

### Technologies Used

- **JavaScript**: For scripting the functionality of the extension.
- **Chrome Extension API**: To integrate with the Chrome browser.
- **Web Speech API**: For voice recognition functionality.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
