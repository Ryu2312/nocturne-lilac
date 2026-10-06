# Lilac Ember

A dark Visual Studio Code theme with a neutral interface and soft lilac, pink, orange, and green syntax accents. Includes custom method-call highlighting and `void` highlighting for JavaScript, TypeScript, JSX, and TSX.

## Preview

> Screenshots coming soon.

## Color Palette

| Purpose    | Color     |
| ---------- | --------- |
| Background | `#1A1A1A` |
| Foreground | `#EDEDED` |
| Lilac      | `#B897F4` |
| Soft Lilac | `#BDA0F1` |
| Pink       | `#F8A6C8` |
| Orange     | `#F1A275` |
| Green      | `#83D19B` |
| Comments   | `#808080` |

## Features

Lilac Ember includes syntax colors for:

- Keywords and operators
- Types, classes, interfaces, and namespaces
- Functions and methods
- Variables and parameters
- Strings and template literals
- Regular expressions
- Numbers and boolean/null values
- `this` and `super`
- `new Class()` expressions
- JSON properties and values
- Comments
- Git decorations
- VS Code Explorer and editor UI

Small TextMate grammar injections add method-call highlighting and a distinct color for `void` in JavaScript (`.js`), TypeScript (`.ts`), JSX (`.jsx`), and TSX (`.tsx`). These injections ignore comments and strings.

## Installation

### From a VSIX

Create a local extension package and install it:

```bash
npx @vscode/vsce package
code --install-extension lilac-ember-0.1.2.vsix
```

After installation, open **Preferences → Color Theme** and select **Lilac Ember**.

### Development

Clone the repository and open the project in VS Code:

```bash
git clone https://github.com/Ryu2312/nocturne-lilac.git
cd nocturne-lilac
code .
```

Press `F5` to launch the **Extension Development Host**, then select **Lilac Ember** from **Preferences → Color Theme**.

## Project files

- Color theme: `themes/Lilac Ember-color-theme.json`
- `void` highlighting: `syntaxes/typescript-void.tmLanguage.json`
- Method-call highlighting: `syntaxes/typescript-methods.tmLanguage.json`

## License

MIT
