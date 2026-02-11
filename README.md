# Kanagawa Colors Theme for JetBrains

A JetBrains IDE theme inspired by [kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) — the colors of the famous painting by Katsushika Hokusai.

## Variants

### Wave (Dark Default)
The default dark theme with deep ocean-inspired colors. Rich contrast with warm foreground tones against cool dark backgrounds.

### Dragon (Dark Muted)
A more subdued dark variant with earthy, muted tones. Lower contrast for extended coding sessions.

### Lotus (Light)
A warm light theme with parchment-inspired backgrounds and rich, saturated syntax colors.

## Installation

### From JetBrains Marketplace
1. Open your JetBrains IDE
2. Go to **Settings** > **Plugins** > **Marketplace**
3. Search for "Kanagawa Colors Theme"
4. Click **Install** and restart the IDE

### From Disk
1. Download the latest release `.zip` from [Releases](https://github.com/followLemmi/jetbrains-kanagawa-colors/releases)
2. Go to **Settings** > **Plugins** > gear icon > **Install Plugin from Disk...**
3. Select the downloaded `.zip` file and restart the IDE

### Activate
Go to **Settings** > **Appearance & Behavior** > **Appearance** > **Theme** and select one of:
- Kanagawa Wave
- Kanagawa Dragon
- Kanagawa Lotus

## Compatibility

- IntelliJ IDEA 2024.2+ (New UI / Islands)
- All JetBrains IDEs based on IntelliJ Platform 2024.2+

## Building from Source

```bash
./gradlew buildPlugin
```

The plugin ZIP will be created in `build/distributions/`.

To test in a sandboxed IDE instance:

```bash
./gradlew runIde
```

## Credits

- Color palette by [rebelot/kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim)
- Inspired by "The Great Wave off Kanagawa" by Katsushika Hokusai

## License

[MIT](LICENSE)
