# UML2SVG VS Code Extension

## Overview

The UML2SVG extension for Visual Studio Code allows you to easily convert PlantUML diagrams into SVG images using a custom PlantUML server. This extension provides a simple way to visualize your UML diagrams and includes a feature to copy the SVG code directly to your clipboard.

## Features

- Convert PlantUML diagrams to SVG images.
- Display SVG images in a preview panel.
- Copy SVG code to clipboard with a single click.

## Usage

1. **Open a PlantUML File**: Open any `.uml` file in Visual Studio Code.
2. **Preview the UML Diagram**: Use the command `View UML` to open a preview panel displaying the SVG image of your UML diagram.
3. **Copy SVG Code**: Click the "Copy SVG Code" button in the preview panel to copy the SVG code to your clipboard.

## Installation

1. **Download the Extension**: Download the `.vsix` file of this extension.
2. **Install the Extension**:
   - Open the Extensions view in VS Code (Ctrl+Shift+X).
   - Click on the three-dot menu on the top-right corner.
   - Select "Install from VSIX...".
   - Navigate to your `.vsix` file and install it.

## Requirements

- Visual Studio Code
- An internet connection to communicate with the PlantUML server.

## Extension Settings

This extension contributes the following settings:

- `uml2svg.serverUrl`: The URL of the PlantUML server to use for rendering SVG images.

## Example

Here's an example of a PlantUML diagram you can try:

```text
@startuml
Alice -> Bob: Hello Bob, how are you?
Bob --> Alice: I am good thanks!
@enduml
```

Save the above text in a `.uml` file and use the `View UML` command to see the rendered SVG image.

## Contributing

If you find any issues or have suggestions for new features, please open an issue or submit a pull request on this [GitHub repository](https://github.com/connectplatform/uml2svg-vscode-extension).

## License

This extension is licensed under the MIT License.

## Release Notes

### 0.0.1

- Initial release of UML2SVG extension.

---

**Enjoy!**