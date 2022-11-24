# New Darcula VSCode theme
A modern take on the [Jetbrains](https://www.jetbrains.com/webstorm/) Darcula theme. Leave a review at [VS Marketplace Repo](https://marketplace.visualstudio.com/items?itemName=e-simpson.new-darcula)! :)

![Screenshot](https://raw.githubusercontent.com/e-simpson/new-darcula/main/images/screenshot.png)

To achieve this look:
- Install [JetBrains Icon Theme](https://marketplace.visualstudio.com/items?itemName=chadalen.vscode-jetbrains-icon-theme) extension
- Install [CustomizeUI](https://marketplace.visualstudio.com/items?itemName=iocave.customize-ui) extension
- Install [Fix VSCode Checksums](https://marketplace.visualstudio.com/items?itemName=lehni.vscode-fix-checksums) extension
- Install [JetBrains Mono](https://www.jetbrains.com/lp/mono) font
- Add the following to your VSCode settings.json (>Open User Settings (JSON))
```
{
    "window.titleBarStyle": "custom",
    "editor.minimap.enabled": false,
    "customizeUI.activityBar": "top",
    "editor.fontSize": 13,
    "editor.fontFamily": "Jetbrains Mono, Menlo, Monaco, 'Courier New', monospace",
    "editor.bracketPairColorization.enabled": true,`
    ...
}
```

## Language Support
- Javascript
- TypeScript
- React, Svelte, Vue, Angular
- GraphQL
- HTML
- PHP
- Markdown
- JSON
- shell script (.sh)
- CSS, SCSS, TailwindCSS, styled-components
- Dockerfile, Docker compose file

## Contribution
If you want something added like additional syntax highlighting, feel free to make a pull request.

## License
MIT

