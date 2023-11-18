# VS Code Plugin for js handlers SIER

https://github.com/webandr/mongit 

inspired by https://canonium.com/articles/creating-plugin-for-vscode-theory-and-standard-plugin
https://stackoverflow.com/questions/55771578/cant-find-the-module-after-extension-is-installed 
https://code.visualstudio.com/api/working-with-extensions/publishing-extension#packaging-extensions 
vsce package - создать инсталляц пакет
code --install-extension vscode-mongit-1.0.0.vsix - локально установить расширение без магазина расширений

## Install

  * Press `F1` and select `Extensions: Install Extensions`.
  * Search for and select `mongit`.

See the [extension installation guide](https://code.visualstudio.com/docs/editor/extension-gallery) for details.

## Usage

Press `F1` and run the command named `mongit: proceed JavaScript code`.

## Supported languages

  * JavaScript


## Keyboard shortcuts

For changes keyboard shortcuts, create a new rule in `File -> Preferences -> Keyboard Shortcuts`:

```json
{
  "key": "ctrl+alt+m",
  "command": "mongit.save"
}
```

## Changelog

See the [Releases section of our GitHub project] (https://github.com/webandr/mongit/releases) for changelogs for each release version.

## License

This software is released under the terms of the MIT license.
