# Futuristic Glass UI for VS Code

A custom dark color theme with midnight-blue surfaces, luminous cyan focus accents, cool-blue identifiers, violet keywords, and soft mint strings.

> **Glass-inspired, not literal blur:** VS Code color themes can style editor/UI colors, but cannot create true backdrop blur in the editor chrome. This theme uses layered dark surfaces, fine borders, and bright edges to create a glassmorphism-inspired look.

## Palette

| Role | Color |
|---|---|
| Editor background | `#081321` |
| Side panels | `#0A1526` |
| Cyan focus accents | `#66E3FF` |
| Blue functions | `#9DBBFF` |
| Violet keywords | `#D1A7FF` |
| Mint strings | `#A7E6BC` |
| Warm numbers | `#FFC889` |

## Try it locally

1. Open this `vscode-theme` folder in VS Code.
2. Press **F5** to start an Extension Development Host.
3. In the new window, open the Command Palette with `Ctrl+Shift+P`.
4. Run **Preferences: Color Theme**.
5. Select **Futuristic Glass UI**.

## Build an installable VSIX

Requires Node.js and npm.

```bash
npm install --global @vscode/vsce
vsce package
```

VS Code will create a `.vsix` package in this folder. Install it using **Extensions → … → Install from VSIX…**.

## Language highlighting

Includes TextMate scopes and semantic colors for common web-development languages and file types, including PHP, JavaScript/TypeScript, HTML, CSS, JSON, Markdown, and diffs. Semantic coloring depends on the active language extension.

## Project files

- `package.json` — extension manifest
- `themes/futuristic-glass-ui-color-theme.json` — editor and syntax palette
- `.vscode/launch.json` — extension development launch config

## Credits

Created by [Ansh Singh](https://github.com/ansh55560-ui).

## License

MIT
