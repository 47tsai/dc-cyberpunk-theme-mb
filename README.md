# Cyberpunk 2077: Night City (Venus)

A Cyberpunk 2077-inspired dark theme for Discord on **Venus for Android**.

This is an Android/Venus adaptation of the color palette and visual direction in [Wosiu6/cyberpunk2077-discord-theme](https://github.com/Wosiu6/cyberpunk2077-discord-theme). It translates the desktop theme's neon red, cyan, purple and yellow accents into Venus's Revenge-compatible JSON theme format.

## Preview direction

- **Base:** near-black Night City surfaces
- **Primary accent:** neon red `#C5003C`
- **Text and interactive accent:** neon cyan `#55EAD4`
- **Secondary accents:** electric blue `#00B8FF`, neon purple `#BD00FF`, signal yellow `#F3E600`
- **Wallpaper:** the original project's Night City image, loaded remotely

The theme is intentionally dark across Discord's dark, light, midnight and darker appearance slots.

## Install

1. Open **Venus Settings** in Discord.
2. Open **Custom themes**.
3. Paste this raw theme URL into the theme URL field:

   `https://raw.githubusercontent.com/47tsai/dc-cyberpunk-theme-mb/main/theme.json`

4. Tap **Install**, then enable the installed theme if needed.

If Venus changes its theme screen or URL handling in a later release, use the JSON file directly from this repository.

## Notes

- The theme uses Venus's `spec: 2` JSON format.
- Wallpaper loading requires an internet connection. If the original wallpaper URL becomes unavailable, the colors will still work without it.
- Desktop-only CSS effects, layout selectors, custom fonts and plugin styling do not translate to Android's token-based theme system. This port focuses on colors and the supported chat wallpaper.
- The original wallpaper is referenced remotely and is not copied into this repository.

## Credits and licensing

- Android/Venus adaptation: © 2026 47tsai.
- Original desktop theme: [Wosiu6/cyberpunk2077-discord-theme](https://github.com/Wosiu6/cyberpunk2077-discord-theme), © 2025 Patryk Wos.
- The upstream project is licensed under Apache License 2.0 and is a customized fork of [ClearVision-v7](https://github.com/ClearVision/ClearVision-v7). See [LICENSE](LICENSE) and [NOTICE](NOTICE) for retained attribution.
- Cyberpunk 2077 and related intellectual property are owned by their respective rights holders. This project is unofficial and is not affiliated with or endorsed by CD PROJEKT RED.

## Files

- `theme.json`: Venus custom theme.
- `LICENSE`: Apache License 2.0.
- `NOTICE`: upstream attribution and adaptation notice.
