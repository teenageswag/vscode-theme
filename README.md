# Minimal Dark

A refined, minimal dark theme for Visual Studio Code, inspired by the **Minimal Blur** aesthetic from Zed. Designed for focus and clarity.

## 🎨 Palette

- **Background**: Deep Charcoal (`#141414`)
- **Text**: Balanced Gray (`#BFBFBF`)
- **Accents**: Muted Gold (`#CCB333`)
- **Success**: Soft Green (`#73B82E`)

## 🚀 Installation

### Download from GitHub

You can download the latest compiled extension (`.vsix`) from the **[Releases]([https://github.com/teenageswag/Visual-Studio-Config/releases](https://github.com/teenageswag/Visual-Studio-Config/releases/))** section.
After downloading:

1. Open VS Code.
2. Go to the **Extensions** view (`Ctrl+Shift+X`).
3. Click on the `...` (Views and More Actions) at the top right.
4. Select **Install from VSIX...** and choose the downloaded file.

### Manual Installation

1. Copy the `Visual-Studio-Theme` folder to your VS Code extensions directory:
        - **Windows**: `%USERPROFILE%\.vscode\extensions`
        - **macOS/Linux**: `~/.vscode/extensions`
2. Restart VS Code.
3. Press `Ctrl+K Ctrl+T` and select **Minimal Dark**.

## 🛠️ Build and Development

To build the project into a `.vsix` package:

1. Install `vsce` (Visual Studio Code Extension Manager):

   ```bash
   npm install -g @vscode/vsce
   ```

2. Run the packaging command:

   ```bash
   vsce package
   ```

   This will generate a `.vsix` file in the root directory.

If you want to modify the theme:

1. Clone this repository.
2. Open the folder in VS Code.
3. Edit `themes/MinimalDark.json`.
4. Press `F5` to open a new window with your changes applied for testing.

---
Created with ❤️ by [j2cks](https://github.com/teenageswag)
