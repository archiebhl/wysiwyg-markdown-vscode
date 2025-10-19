# Fork Information

Features:
- Fixed issues brought about by using Crepe for fenced code, such as buggy typing and erratic caret movements.
- The plugin now acts as the default markdown editor. 

For devs: 
1. Install dependencies with `pnpm install`.
2. Package with `pnpm run package`.
3. Run the code. 

The original readme is below:

# Milkdown 💖 VSCode

Edit markdown in a WYSIWYG way, powered by [milkdown](https://saul-mirone.github.io/milkdown/#/).

## Install

[VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=mirone.milkdown)

## Features

> Plugin is still in dev progress, this is an early access version.

![Show](https://raw.githubusercontent.com/Saul-Mirone/milkdown-vscode/main/milkdown-vscode.gif)

### Usage:

-   Right click in editor to open in milkdown.
-   Right click in explorer bar and select open in milkdown.
-   Search `Milkdown` in command palette with `Cmd/Ctrl + Shift + P`.

### Feature List

-   WYSIWYG Markdown Editor
-   Full GFM syntax support
-   Emoji picker and filter
-   Copy and paste with markdown
-   Slash commands
-   Tooltip bar
-   Math support

### Set as Default
(No longer relevant in the fork)
If you want to use milkdown as your default markdown, you can add this config into your settings:

```json
"workbench.editorAssociations": {
    "*.md": "milkdown.editor"
}
```

# Contributor

<a title="Saul Mirone" href="https://github.com/Saul-Mirone"><img src="https://avatars.githubusercontent.com/u/10047788?v=4" width="100" alt="profile picture of Saul Mirone"></a>
<a title="calvinfung" href="https://github.com/hereisfun"><img src="https://avatars.githubusercontent.com/u/20593467?v=4" width="100" alt="profile picture of calvinfung"></a>

## License

[MIT](https://github.com/Saul-Mirone/milkdown-vscode/blob/main/LICENSE)
