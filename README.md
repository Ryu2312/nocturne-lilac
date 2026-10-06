# Lilac Ember

A dark Visual Studio Code theme focused on a clean, low-distraction interface with soft lilac, pink, orange, green, and neutral tones.

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

## Highlights

Lilac Ember provides custom highlighting for:

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

The theme also includes a small TypeScript grammar extension to give `void` its own color without affecting other primitive types.

## Installation

### Development

Clone the repository and open it with Visual Studio Code:

```bash
git clone <repository-url>
cd lilac-ember
code .
```

Press `F5` to launch the **Extension Development Host** and preview the theme.

Then open:

```text
Preferences → Color Theme
```

and select:

```text
Lilac Ember
```

### Extension package

The theme can be packaged as a VS Code extension and installed locally using a `.vsix` package.

## Development

The theme is built as a standard Visual Studio Code color theme extension.

Main theme file:

```text
themes/
└── lilac-ember-color-theme.json
```

TypeScript grammar extension:

```text
syntaxes/
└── typescript-void.tmLanguage.json
```

## Version

**0.1.0**

This is the first development version of Lilac Ember.

## License

MIT
