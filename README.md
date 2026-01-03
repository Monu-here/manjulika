# Manjulika Ember Theme

Deep sindoor reds and warm temple ambers for a classic, moody coding vibe.

A dark theme inspired by Indian temples and rituals—rich reds, warm golds, and soft ambers create a powerful, haunting presence perfect for focused coding.

## Features

✨ **All-Yellow Typography** – All code text renders in warm amber (#e2b35b) for a unified, cohesive look  
🔥 **Deep Ember Base** – Dark background (#0b0807) reduces eye strain while keeping the theme vibrant  
🎨 **Classic Aesthetic** – Warm reds and golds reminiscent of traditional ceremonies  
💬 **Semantic Highlights** – Comments in muted sepia for subtle distinction  

## Preview

### Code Example
```javascript
// Your code here appears in warm amber
const message = "Hello, World!";
function greet(name) {
  console.log(`Welcome, ${name}!`);
}
```

**All text displays in beautiful warm yellow (#e2b35b)**

## Installation

### From VS Code Extensions Marketplace
*(Coming soon)*

### From .vsix File
1. Download `manjulika-by-monu-0.0.8.vsix` from releases
2. Open VS Code → Command Palette (`Ctrl+Shift+P`)
3. Type: `Extensions: Install from VSIX`
4. Select the downloaded file
5. Choose the **Manjulika Ember** theme: Command Palette → `Color Theme` → **Manjulika Ember**

### Manual Installation
```bash
# Clone or download the repo
git clone https://github.com/Monu-here/manjulika.git
cd manjulika

# Install extension in development mode
npm install
npx @vscode/vsce package --allow-missing-repository --no-dependencies
code --install-extension ./manjulika-by-monu-0.0.8.vsix
```

## Recommended Editor Settings

Add to your VS Code `settings.json` for the full italic/cursive experience:

```json
"[Manjulika Ember]": {
  "editor.fontFamily": "'Patrick Hand', 'Fira Code', monospace",
  "editor.fontLigatures": false,
  "editor.cursorStyle": "line",
  "editor.cursorBlinking": "smooth",
  "editor.lineHeight": 24,
  "editor.letterSpacing": 0.5
}
```

## Color Palette

| Element | Color | Hex |
|---------|-------|-----|
| Background | Deep Ember | #0b0807 |
| Main Text | Warm Amber | #e2b35b |
| Cursor | Amber | #e2b35b |
| Selection | Dark Red | #26130f |
| Activity Bar | Very Dark | #110b0a |
| Line Highlight | Dark Brown | #16100e |

## Customization

To customize the theme, edit `themes/manjulika-color-theme.json`:

```json
{
  "colors": {
    "editor.background": "#0b0807",
    "editor.foreground": "#e2b35b",
    "editorCursor.foreground": "#e2b35b"
  },
  "tokenColors": [...]
}
```

Rebuild with:
```bash
npx @vscode/vsce package --allow-missing-repository --no-dependencies
```

## License

MIT – Free to use and modify

## Release Notes

### v0.0.8
- All code text unified to warm amber (#e2b35b)
- Semantic token colors enforced globally
- Deep ember background for reduced eye strain
- Professional dark theme with classic aesthetic

### v0.0.1
- Initial release with ember and amber palette

## Support & Feedback

Found a bug or have suggestions?  
- [GitHub Issues](https://github.com/Monu-here/manjulika/issues)
- [GitHub Discussions](https://github.com/Monu-here/manjulika/discussions)

**Enjoy the Manjulika Ember Theme! 🔥**
