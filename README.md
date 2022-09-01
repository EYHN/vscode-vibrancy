# The project is not actively maintained. To continue please move to [illixion/vscode-vibrancy-continued](https://github.com/illixion/vscode-vibrancy-continued)

# Visual Studio Code Extension - Vibrancy

> Windows 10 users may have a slight mouse lag when moving the window, [please read here for details](https://github.com/EYHN/vscode-vibrancy/discussions/80).

> Starting from v1.0.10, this extension no longer supports Windows 7.

> For questions about installation and uninstallation, please read [FAQs](#FAQs).

Enable Acrylic/Glass effect for your VS Code.

![screenshot](./screenshot.png)

[![](https://vsmarketplacebadge.apphb.com/version/eyhn.vscode-vibrancy.svg)](https://marketplace.visualstudio.com/items?itemName=eyhn.vscode-vibrancy)&nbsp;
[![](https://img.shields.io/visual-studio-marketplace/stars/eyhn.vscode-vibrancy.svg)](https://marketplace.visualstudio.com/items?itemName=eyhn.vscode-vibrancy)

![](https://img.shields.io/badge/Vistual%20Studio%20Code%20v1.57.0-Tested%20%E2%9C%94%EF%B8%8F-brightgreen?logo=Visual-Studio-Code&logoColor=ffffff)

[![](https://img.shields.io/github/stars/eyhn/vscode-vibrancy.svg?style=social)](https://github.com/eyhn/vscode-vibrancy)&nbsp;
[![](https://img.shields.io/github/watchers/eyhn/vscode-vibrancy.svg?style=social)](https://github.com/eyhn/vscode-vibrancy)

Links: [Github](https://github.com/eyhn/vscode-vibrancy) | [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=eyhn.vscode-vibrancy) | [issues](https://github.com/eyhn/vscode-vibrancy/issues)

[中文教程 (Chinese README)](https://eyhn.in/vscode-vibrancy/)

## Supported Operating Systems

Windows 10 ✔

MacOS ✔

## Getting Started

1. Make sure the color theme you selected is the 'Dark+ (default)'

![step-1](./step-1.png)

2. Install this extension from [the Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=eyhn.vscode-vibrancy).

3. Press F1 and Activate command "Reload Vibrancy".

![step-3](./step-3.png)

4. Restart.

Every time after Code is updated, please re-enable vibrancy.

## Warning

This extension works by editting VS Code's css file. So, a prompt will appear when installing `vscode-vibrancy` for the first time or each time VS Code updates. U can click [never show again] to hide it.

![screenshot](./warns.png)

To fix the "[Unsupported]" warning on VS Code's title bar, please refer to this extension: [Fix VSCode Checksums](https://marketplace.visualstudio.com/items?itemName=lehni.vscode-fix-checksums).

## Options

#### vscode_vibrancy.type

Native method of Vibrancy Effect.

* auto : Automatically switch with system version.
* acrylic : (Windows 10 only) Fluent Design blur.
* appearance-based, light, dark, titlebar, selection, menu, popover, sidebar, medium-light, ultra-dark: (MacOS only)

#### vscode_vibrancy.opacity

Opacity of Vibrancy Effect.

*value: 0.0 ~ 1*

#### vscode_vibrancy.theme

Select Vibrancy theme:

* Default Dark
* Dark (Only Subbar)
* Default Light
* Light (Only Subbar)
* Noir et blanc

|        Default Dark      |    Dark (Only Subbar)   |          Noir et blanc         |
|:------------------------:|:-----------------------:|:------------------------------:|
| ![](./theme-default.jpg) | ![](./theme-subbar.jpg) | ![](./theme-noir-et-blanc.jpg) |

> You can contribute more themes for us! [see here](https://github.com/EYHN/vscode-vibrancy/tree/master/themes).

#### vscode_vibrancy.imports

Import CSS/JS files, as file paths.

EXAMPLE: `C:/Users/MyUserName/Documents/custom.css`

*value: array[]*

## FAQs

### How to uninstall?

Press F1 and Activate command "Disable Vibrancy", and Restart Visual Studio Code.

### Effect doesn't work for terminal?

Check your settings. You should change the renderer type of the terminal to dom.

`"terminal.integrated.gpuAcceleration": "off"`

### Prompt "Run Visual Studio Code with administrator privileges" ?

It usually appears on windows when you are using the VSCode System Installer. You should close VSCode completely, then run VSCode as administrator and retry what you did before (Enable/Reload/Disable Vibrancy).

## Thanks ⭐

[be5invis/vscode-custom-css](https://github.com/be5invis/vscode-custom-css) : The basis of this extension program

[DIYgod](https://github.com/microsoft/vscode/issues/32257#issuecomment-509936623) : Fix issues with VSCode 1.36
