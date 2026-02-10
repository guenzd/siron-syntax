# Siron Syntax Highlighting for VS Code

This extension provides syntax highlighting for Siron programming language files (`.siron`) optimized for dark themes.

## Features

- Syntax highlighting for Siron keywords, operators, and comments
- Support for code folding (beginn-benutze/schleife blocks)
- Block comments with `*` ... `%`
- String literals with single quotes
- Case-insensitive keyword matching
- Optimized color scheme for dark themes (compatible with themes like Smyket)

## Installation

1. Copy this folder to your VS Code extensions directory:
   - **macOS/Linux**: `~/.vscode/extensions/`
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`

2. Restart VS Code

3. Open any `.siron` file to see syntax highlighting

## Syntax Elements

- **Control Flow Keywords** (magenta): `abbruch`, `benutze-bloecke`, `ende`, `endverarbeitung`, `hole`, `modul`, `sort`, `stop`, `beginn-benutze`, `schleife`, `ende-benutze`, `ende-schleife`
- **Main Keywords** (blue): `aendere`, `benutze`, `commit`, `dann`, `drucke`, `ende-gw`, `ergaenze`, `falls`, `gzeiger`, `ident`, `lies`, `liste`, `merke`, `mische`, `nimm`, `schreibe`, `sofern`, `sonst`, `tabelle`, `wechsel`, `wenn`
- **Secondary Keywords** (light blue): `abfrage`, `adatei1-6`, `als`, `anfangswert`, `auf`, `bei`, `datei`, `eq`, `fuer`, `ge`, `gt`, `kein`, `konstant`, `kopf`, `le`, `listpara`, `lt`, `mit`, `ne`, `neu`, `oder`, `ohne`, `protokoll`, `ram-i`, `ram-s`, `satz`, `ueber`, `und`, `vom`, `von`, `xml`, `zeichen`, `zeile`
- **Comments**: Block comments between `*` and `%`
- **Strings**: Single-quoted strings
- **Operators**: `(`, `)`, `,`, `=`

## License

MIT
