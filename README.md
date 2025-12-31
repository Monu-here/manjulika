# Manjulika Ember Theme

Deep sindoor reds and warm temple ambers for a classic, moody coding vibe.

## Highlights
- Dark base with ember accents for gentle contrast.
- Warm syntax: ember keywords, amber strings, gold functions, sepia comments.
- Optional cursive/italic feel via recommended font stack.

## Install locally
1. Package: `npx @vscode/vsce package --allow-missing-repository --no-dependencies`
2. Install: `code --install-extension manjulika-by-monu-0.0.1.vsix`
3. Switch theme: Command Palette → `Color Theme` → **Manjulika Ember**.

## Recommended editor settings
If you like the cursive/italic look:
```json
"editor.fontFamily": "'Patrick Hand', 'Fira Code', cursive",
"editor.fontLigatures": false,
"editor.cursorStyle": "line",
"editor.cursorBlinking": "smooth"
```

## Develop
- Watch/compile: `npm run watch`
- Package: `npx @vscode/vsce package --allow-missing-repository --no-dependencies`
- Test install: `code --install-extension ./manjulika-by-monu-0.0.1.vsix`

## Publish (optional)
1. Create/login publisher: `vsce create-publisher <name>` then `vsce login <name>`.
2. Release: `vsce publish patch` (or `minor`/`major`).
