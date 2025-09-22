# Systemset VS Code Theme

A professional Visual Studio Code theme inspired by the **Systemset brand**, featuring beautiful green gradients and modern minimalistic design.

## 🎨 Theme Variants

## 📸 Screenshots

### Systemset Dark
A sleek dark theme with pure black backgrounds and vibrant green accents that's perfect for long coding sessions and reduces eye strain.

![Systemset Dark Preview](https://github.com/Systemsetco/SystemsetTheme/blob/main/assets/preview-dark.png)

### Systemset Light  
A clean light theme with crisp white backgrounds and carefully balanced green highlights for those who prefer bright interfaces.

![Systemset Light Preview](https://github.com/Systemsetco/SystemsetTheme/blob/main/assets/preview-light.png)

## 🌈 Color Palette

The theme is built around the official Systemset brand colors:

| Color | Hex Code | Usage |
|-------|----------|--------|
| **Primary Green** | `#6EE54E` | Keywords, active elements, cursors |
| **Darker Green** | `#2EBF46` | Functions, classes, secondary highlights |
| **Accent Yellow-Green** | `#D8F060` | Strings, constants, special elements |
| **Deep Black** | `#000000` | Dark theme backgrounds |
| **Pure White** | `#FFFFFF` | Light theme backgrounds, dark theme text |
| **Charcoal Gray** | `#1E1E1E` | Dark theme secondary backgrounds |
| **Light Gray** | `#B0B0B0` | Comments, inactive elements |

## ✨ Features

- **🎯 Brand-Aligned**: Perfectly matches Systemset's visual identity
- **👀 Eye-Friendly**: Carefully chosen contrast ratios for optimal readability
- **🌟 Modern Design**: Clean, minimalistic interface with subtle gradients
- **📝 Comprehensive**: Supports all major programming languages and file types
- **🔧 Consistent**: Unified color scheme across all VS Code elements
- **⚡ Performance**: Lightweight and fast-loading theme files

## 🚀 Installation

### From VS Code Marketplace (Recommended)
1. Open VS Code
2. Press `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (macOS) to open Extensions
3. Search for "Systemset Theme"
4. Click **Install**
5. Go to `File > Preferences > Color Theme` (or `Code > Preferences > Color Theme` on macOS)
6. Select either **Systemset Dark** or **Systemset Light**

### Manual Installation
1. Download the theme files
2. Copy the folder to your VS Code extensions directory:
   - **Windows**: `%USERPROFILE%\.vscode\extensions`
   - **macOS**: `~/.vscode/extensions`
   - **Linux**: `~/.vscode/extensions`
3. Restart VS Code
4. Go to `File > Preferences > Color Theme`
5. Select your preferred Systemset theme

### Development Installation
1. Clone this repository
2. Copy the folder to your VS Code extensions directory
3. Restart VS Code or press `F5` to open a development host

## 🛠️ Customization

You can customize the theme by modifying the JSON files in the `themes/` directory:

- `systemset-dark-color-theme.json` - Dark variant settings
- `systemset-light-color-theme.json` - Light variant settings

### Common Customizations

To change the cursor color, modify the `editorCursor.foreground` property:

```json
{
  "colors": {
    "editorCursor.foreground": "#your-color-here"
  }
}
```

To adjust syntax highlighting, modify the `tokenColors` array:

```json
{
  "tokenColors": [
    {
      "name": "Comments",
      "scope": ["comment"],
      "settings": {
        "foreground": "#your-color-here",
        "fontStyle": "italic"
      }
    }
  ]
}
```

## 📸 Screenshots

### Dark Theme
- Pure black editor background (`#000000`)
- Vibrant green syntax highlighting
- Subtle green accents in UI elements

### Light Theme  
- Clean white editor background (`#FFFFFF`)
- Professional green color scheme
- High contrast for excellent readability

## 🎯 Supported Languages

The Systemset theme provides excellent syntax highlighting for:

- **Web Technologies**: HTML, CSS, SCSS, JavaScript, TypeScript, React, Vue, Angular
- **Backend Languages**: Python, Java, C#, PHP, Ruby, Go, Rust
- **Data & Config**: JSON, YAML, XML, TOML, INI
- **Documentation**: Markdown, reStructuredText
- **Database**: SQL, NoSQL query languages
- **DevOps**: Docker, Kubernetes, CI/CD configurations
- **And many more!**

## 🤝 Contributing

We welcome contributions to improve the Systemset theme! Here's how you can help:

1. **Fork** this repository
2. **Create** a new branch for your feature (`git checkout -b feature/amazing-feature`)
3. **Make** your changes to the theme files
4. **Test** your changes thoroughly
5. **Commit** your changes (`git commit -m 'Add amazing feature'`)
6. **Push** to your branch (`git push origin feature/amazing-feature`)
7. **Open** a Pull Request

### Development Setup

```bash
# Clone the repository
git clone https://github.com/systemset/SystemsetTheme
cd SystemsetTheme

# Install dependencies (if any)
npm install

# Open in VS Code
code .
```

## 📝 Changelog

### Version 1.0.0
- 🎉 Initial release
- ✨ Added Systemset Dark theme
- ✨ Added Systemset Light theme
- 🎨 Implemented full Systemset brand color palette
- 📚 Comprehensive language support
- 🔧 Optimized for VS Code latest features

## 📄 License

This theme is released under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## 🏢 About Systemset

This theme is created with ❤️ for the Systemset brand and community. 

**Systemset** is committed to delivering high-quality, professional tools and experiences. This VS Code theme reflects our dedication to clean design, functionality, and brand consistency.

## 🌟 Show Your Support

If you enjoy using the Systemset theme, please:

- ⭐ **Star** this repository
- 🐛 **Report** any issues you find
- 💬 **Share** it with your fellow developers
- 📝 **Leave a review** on the VS Code Marketplace

---

**Happy Coding with Systemset! 🚀**

*Made with 💚 for developers everywhere*