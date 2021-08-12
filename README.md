# README

## Personal VSCode Theme

This is a personal theme for VSCode. It's based off of Monokai Pro and Gotham.

### To use this theme

```
git clone git@github.com:joshloftis/verydarkmonokai_vscode_theme.git
cd verydarkmonokai_vscode_theme
rm -rf .git
```

(The last command isn't necessary, but there really isn't any need for you to have this repo versioned with git once downloaded.)

If on a Mac...

```
cd ..
cp -a verydarkmonokai_vscode_theme ~/.vscode/extensions/
```

If on PC, all you need to do is move the `verydarkmonokai_vscode_theme` directory into the `extensions` directory for VSCode, but I'm not sure how this is done for Windows...

Finally, launch VSCode

```
code .
```

In VSCode select `Code > Perferences > Color Theme` or `⌘ K ⌘ T`. Finally, select `Darker Monokai`.

The icon set is the same set from Monokai Pro. Feel free to replace these icons with whatever icon pack you prefer.

To use the icon theme, in VSCODE select `Code > Perferences > File Icon Theme` and then select `very_dark_monokai_icons`.

I also suggest installing and using Operator Mono - a great font for coding!

### What the theme looks like:

![No open files](/images/no-open-files.png?raw=true)
![With file open](/images/with-open-file.png?raw=true)

(I think the screenshots darken the colors a bit. The theme is dark, yes, but a bit lighter I think than these images reveal. The text is also more vibrant.)

I also suggest the following VSCode Settings, but these are highly opinionated and obviously optional:

```json
{
  "workbench.colorTheme": "Darker Monokai",
  "workbench.iconTheme": "very_dark_monokai_icons",
  "workbench.editor.tabSizing": "shrink",
  "editor.fontSize": 14,
  "editor.fontFamily": "OperatorMono-Book, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "editor.parameterHints.enabled": false,
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "explorer.sortOrder": "default",
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
}
```

**Enjoy!**
