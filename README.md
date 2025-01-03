# darkmode-extension
A Chrome extension that allows you to toggle between light and dark mode on any website.
# Appearance - Chrome Extension

Appearance is a Chrome extension that allows you to easily switch between light and dark mode on any website. This project was developed as a way to gain a better understanding of JSON files and their use in Chrome extensions.

## Motivation

JSON (JavaScript Object Notation) is a lightweight data interchange format that is easy for humans to read and write, and easy for machines to parse and generate. It is often used in web development, including the creation of Chrome extensions, where it is used to define the extension's metadata, permissions, and other configuration settings.

By creating this Appearance extension, the project aims to provide a practical example of how JSON files are used in the development of a Chrome extension. Through the process of building this project, gained a deeper understanding of the structure and usage of JSON files, as well as how they integrate with the various components of a Chrome extension.

## Features

- Toggle between light and dark mode with a single click
- Applies the mode change to the entire webpage, including images, videos, and other media
- Simple and intuitive user interface

## Installation

1. Download or clone the repository to your local machine.
2. Open the Chrome browser and navigate to `chrome://extensions/`.
3. Enable "Developer mode" by toggling the switch in the top right corner.
4. Click on "Load unpacked" and select the directory where you downloaded the extension.
5. The Appearance extension should now be installed and ready to use.

## Usage

1. Click on the Appearance extension icon in the Chrome toolbar.
2. Toggle the "On/Off" switch to activate or deactivate the dark mode.
3. The website you're currently viewing should instantly switch to the selected mode.

## Files

The repository contains the following files:

1. **manifest.json**: The extension's manifest file, which contains important metadata about the extension.
2. **popup.html**: The HTML file that defines the extension's popup window.
3. **popup.js**: The JavaScript file that powers the extension's functionality.
4. **appOn.js**: The JavaScript file that applies the dark mode styles to the webpage.
5. **appOff.js**: The JavaScript file that applies the light mode styles to the webpage.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open a new issue or submit a pull request. Contributions are always welcome!

## License

This project is licensed under the [MIT License](LICENSE).
