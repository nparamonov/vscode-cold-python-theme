# Cold Python Theme for VS Code

The goal of the Cold Python Theme is to reduce visual clutter and give you more space for your code and thoughts.

<p align="center">
    <a href="https://marketplace.visualstudio.com/items?itemName=nparamonov.cold-python-theme"><img src="https://img.shields.io/visual-studio-marketplace/v/nparamonov.cold-python-theme?style=for-the-badge&colorA=555555&colorB=007ec6&label=VERSION" alt="Version"></a>&nbsp;
    <a href="https://marketplace.visualstudio.com/items?itemName=nparamonov.cold-python-theme"><img src="https://img.shields.io/visual-studio-marketplace/r/nparamonov.cold-python-theme?style=for-the-badge&colorA=555555&colorB=007ec6&label=RATING" alt="Rating"></a>&nbsp;
    <a href="https://marketplace.visualstudio.com/items?itemName=nparamonov.cold-python-theme"><img src="https://img.shields.io/visual-studio-marketplace/i/nparamonov.cold-python-theme?style=for-the-badge&colorA=555555&colorB=007ec6&label=Installs" alt="INSTALLS"></a>&nbsp;
    <a href="https://marketplace.visualstudio.com/items?itemName=nparamonov.cold-python-theme"><img src="https://img.shields.io/visual-studio-marketplace/d/nparamonov.cold-python-theme?style=for-the-badge&colorA=555555&colorB=007ec6&label=Downloads" alt="DOWNLOADS"></a>
</p>

![example](https://raw.githubusercontent.com/nparamonov/vscode-cold-python-theme/main/img/example.png)

I hope this theme will be the one you enjoy working with day and night.

## Features

- Full support for Python syntax
- Beta syntax support for html, templates, css, shell, rst, json, js, batchfile, ini, yaml, toml, ts, dockerfile, jinja2 and some others (in progress)
- Icons theme, inspired by JetBrains ([https://jetbrains.design/intellij/resources/icons_list/](https://jetbrains.design/intellij/resources/icons_list/)) + folders icons
- JetBrains Mono font ready to use (included in icon theme)

## Install

Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=nparamonov.cold-python-theme) and click on the "Install" button.

### Color theme

Set Color Theme ([guide](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme))

![Select the Color Theme](https://raw.githubusercontent.com/nparamonov/vscode-cold-python-theme/main/img/select_color_theme.jpg)

This will give you IDE and syntax highlighting.

### File icon theme

Set File Icon Theme ([guide](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-file-icon-theme))

![Select the File Icon Theme](https://raw.githubusercontent.com/nparamonov/vscode-cold-python-theme/main/img/select_file_icon_theme.jpg)

This will give you file icons shown in the File Explorer and tabbed headings

### Font

It is recommended to use [JetBrains Mono](https://www.jetbrains.com/lp/mono/) font with the Cold Python Theme.

VS Code doesn't provide clear functionality for adding a custom font to a theme... But I managed to add the font to the File icon theme!

> **Important! To use the JetBrains Mono font, the File Icon Theme must be set!**

Then there are 2 ways to enable the new font:

#### Settings UI

![Change font in settings UI](https://raw.githubusercontent.com/nparamonov/vscode-cold-python-theme/main/img/change_font_settings_ui.jpg)

> **It is very important to specify the font family exactly `JetBrainsMono`, without spaces!**

#### settings.json file

Add the following line to your settings.json file:

```json
"editor.fontFamily": "JetBrainsMono, Consolas, 'Courier New', monospace",
```

#### Extras
Also, there are some additional settings that you can apply both in the Settings UI and in settings.json file:

```json
"editor.fontSize": 13,
"editor.fontLigatures": true,
"terminal.integrated.fontFamily": "JetBrainsMono"
```

## Credits

I express my deep gratitude to the JetBrains team for their work. Here are links to open resources used to create the Cold Python theme:

- JetBrains icons: [https://jetbrains.design/intellij/resources/icons_list/](https://jetbrains.design/intellij/resources/icons_list/)
- JetBrains Mono font: [https://www.jetbrains.com/lp/mono/](https://www.jetbrains.com/lp/mono/)
