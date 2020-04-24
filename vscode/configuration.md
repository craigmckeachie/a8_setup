# Visual Studio Code Configuration

1. From the top menus choose`View > Command Palette...`
2. Type the command `open settings`
3. Choose the command `Open Settings (JSON)` from the autocomplete list
4. Copy/Paste the "name":value below into the `settings.json` file.
   > Be sure not to leave any existing settings as shown below and DO NOT copy the comments because comments are not valid in a JSON file and are there just to indicate where any existing settings would be.

`settings.json`

```js
{
 // existing settings here
 // ...

 "editor.fontFamily": "Fira Code iScript, Menlo, Monaco, 'Courier New', monospace",
 "editor.fontLigatures": true,
 "editor.multiCursorModifier": "alt",
 "editor.formatOnSave": true,
 "workbench.iconTheme": "material-icon-theme",
 "emmet.includeLanguages": {"typescript": "html"}

}
```


# Install a font for programming (optional)

If you are interested in trying a new font designed for programming.

1. Install the free [FiraCodeiScript](https://github.com/kencrocken/FiraCodeiScript) font on your system.

- [How to Install Fonts on Windows 10](https://www.groovypost.com/howto/install-fonts-windows-10/)
- [How to Install Fonts on Mac](https://www.dafont.com/faq.php#mac)

2. Close and reopen VS Code to see the new font.

```

```
