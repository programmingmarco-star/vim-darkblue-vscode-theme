# VIM Darkblue Theme for VS Code

A dark blue color theme for Visual Studio Code, ported from the classic VIM Darkblue theme in Eclipse.

## Features

- Deep blue background (#000040) that's easy on the eyes
- High contrast syntax highlighting optimized for Python and other languages
- Carefully selected colors for excellent readability
- Based on the beloved Eclipse VIM Darkblue theme

## Installation

### Manual Installation

1. Download `package.json` and `vim-darkblue-theme.json` from this repository
2. Create a folder named `vim-darkblue-1.0.0` in your VS Code extensions directory:
   - **Windows:** `%USERPROFILE%\.vscode\extensions\`
   - **macOS/Linux:** `~/.vscode/extensions/`
   - **Portable VS Code:** `<VSCode folder>/data/extensions/`
3. Copy both files into the `vim-darkblue-1.0.0` folder
4. Restart VS Code
5. Press `Ctrl+K` then `Ctrl+T` (or `Cmd+K` then `Cmd+T` on Mac)
6. Select "VIM Darkblue" from the list

### Alternative: Direct Settings

Add this to your VS Code `settings.json`:

```json
{
    "workbench.colorCustomizations": {
        "editor.background": "#000040",
        "editor.foreground": "#D0D0D0",
        "editor.lineHighlightBackground": "#000060",
        "editor.selectionBackground": "#A0B0EE",
        "editor.selectionForeground": "#FFFFFF",
        "editorLineNumber.foreground": "#90F020"
    },
    "editor.tokenColorCustomizations": {
        "comments": "#80A0FF",
        "strings": "#FFA0A0",
        "numbers": "#FFFFBB",
        "keywords": "#FFFF60",
        "types": "#60FF60",
        "functions": "#AAFFAA",
        "variables": "#40FFFF"
    }
}
```

## Color Palette

- **Background:** Deep blue (#000040)
- **Foreground:** Light gray (#D0D0D0)
- **Comments:** Light blue (#80A0FF)
- **Strings:** Light red/pink (#FFA0A0)
- **Keywords:** Yellow (#FFFF60)
- **Functions:** Light green (#AAFFAA)
- **Classes:** Bright green (#60FF60)
- **Variables:** Cyan (#40FFFF)
- **Numbers:** Light yellow (#FFFFBB)

## Credits

Original Eclipse theme by ThiefMaster.
Ported to VS Code with love.

## License

MIT License - Feel free to use and modify!
