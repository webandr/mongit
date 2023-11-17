# VS Code Plugin for Lebab

> [Lebab](https://github.com/mohebifar/lebab) transpiles your ES5 code into readable ES2015 (sugar-syntax). It does exactly the opposite of what Babel does.

![VS Code Plugin for Lebab](https://cloud.githubusercontent.com/assets/7034281/17309754/0265b054-5849-11e6-9e64-51d4a19f1180.gif)

## Donate

If you want to thank me, or promote your Issue.

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/mrmlnc)

> Sorry, but I have work and support for plugins and modules requires some time after work. I will be glad of your support or PR's.

## Install

  * Press `F1` and select `Extensions: Install Extensions`.
  * Search for and select `lebab`.

See the [extension installation guide](https://code.visualstudio.com/docs/editor/extension-gallery) for details.

## Usage

Press `F1` and run the command named `Lebab: convert JavaScript code from ES5 to ES2015`.

## Supported languages

  * JavaScript

## Supported settings

**lebab.transforms**

  * Type: `Array`
  * Default: [safe transforms](https://github.com/lebab/lebab#safe-transforms).

All transforms are available in the [official repository Lebab](https://github.com/mohebifar/lebab/blob/master/README.md#features-and-known-limitations).

**lebab.skipWarnings**

  * Type: `Boolean`
  * Default: `true`

Some transforms generate warnings when they cannot be applied. This option disables these messages.

## Keyboard shortcuts

For changes keyboard shortcuts, create a new rule in `File -> Preferences -> Keyboard Shortcuts`:

```json
{
  "key": "ctrl+shift+c",
  "command": "lebab.convert"
}
```

## Changelog

See the [Releases section of our GitHub project](https://github.com/mrmlnc/vscode-lebab/releases) for changelogs for each release version.

## License

This software is released under the terms of the MIT license.
