## Gatot Kaca

Gatot Kaca is a color scheme, customized user interface theme and complete icon set for Visual Studio Code. It has been designed by the Hafizh Maulana Yusliansyah.

## Apply theme

To apply theme, it's so simple. Just open your command palette and type "settings.json". Then you can add the theme like so

```json
{
  "workbench.colorTheme": "Gatot Kaca"
  // ...
}
```

If you care about the title bar style, please make sure you have the titleBarStyle to "custom" like so:

````json
{
    "workbench.colorTheme": "Gatot Kaca",
    "window.titleBarStyle": "custom"
    // ...
}
If you want, I have some recommended settings that you can use.
```bash
{
    "workbench.colorTheme": "Gatot Kaca",
    "editor.lightbulb.enabled": false,
    "editor.selectionHighlight": false,
    "editor.overviewRulerBorder": false,
    "editor.renderLineHighlight": "none",
    "editor.occurrencesHighlight": false,
    "problems.decorations.enabled": false,
    "editor.renderControlCharacters": false,
    "editor.hideCursorInOverviewRuler": true,
}
````

If you like more, please gift me 🌟

## Contribute

I also opened the repo on [github](https://github.com/hafizhmaulanay/gatot-kaca-theme), so for those of you who want to make the theme more robust, or add support for other languages, you can directly make a pull request.
