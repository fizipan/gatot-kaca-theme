# Gatot Kaca for [Visual Studio Code](http://code.visualstudio.com)

> A dark theme for [Visual Studio Code](http://code.visualstudio.com).
> ![Screenshot](https://raw.githubusercontent.com/hafizhmaulanay/gatot-kaca-theme/master/screenshot.png)

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

## Contributing

If you'd like to contribute to this theme, please read the [contributing guidelines](./.github/CONTRIBUTING.md).

## License

[MIT License](./LICENSE)
