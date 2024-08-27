# OpenWRT UCI Highlighter

## Description

**OpenWRT UCI Highlighter** is a Visual Studio Code extension that provides
syntax highlighting for Unified Configuration Interface (UCI) config files used
in OpenWRT. This extension helps in better readability and editing of UCI
configuration files by highlighting various syntax elements.

## Features

- **Syntax Highlighting**: Highlights `package`, `config`, `option`, and `list`
  keywords.
- **String Highlighting**: Supports highlighting of strings enclosed in single
  and double quotes.
- **Comment Highlighting**: Recognizes and highlights comments starting with
  `#`.

## Installation

### Install from VSIX

1. Download the `.vsix` file from the release section or build it using
   `vsce package`.
2. Open Visual Studio Code.
3. Go to the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).
4. Type `Extensions: Install from VSIX...` and select it.
5. Browse to the downloaded `.vsix` file and install it.

### Install from VSCode Marketplace

Currently, this extension is not published to the VSCode Marketplace. For now,
use the `.vsix` installation method.

## Usage

1. Open or create a UCI configuration file in VSCode with the `.uci` extension.
2. The extension will automatically apply syntax highlighting to your file.

## Configuration

No additional configuration is required for basic syntax highlighting. You can
configure VSCode's editor settings to further customize your experience, such as
adjusting font colors or styles.

## Contributing

If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your modifications.
4. Submit a pull request for review.

## License

This extension is licensed under the MIT License. See the [LICENSE](LICENSE)
file for details.

## Contact

For questions or support, please contact the publisher at
[drizt](mailto:drizt@example.com).

## Acknowledgments

This extension uses TextMate grammar for syntax highlighting. Thanks to the
TextMate and VSCode communities for their contributions.
