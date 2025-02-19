# ONScripter-EN-syntax README

Visual Studio Code extension providing syntax highlighting for ONScripter-EN source files.

[Github ONScripter-EN](https://github.com/Galladite27/ONScripter-EN/releases/latest)


Based on the Sky Maker's [NScripter Syntax](https://marketplace.visualstudio.com/items?itemName=SkyMaker.nscripter-syntax) v.1.0.0 Initial Relase

## To package it

install the nodejs' vsce package

```bash
npm install -g @vscode/vsce
```

to package the VSCode Extension :

```bash
vsce package
```

## Release Notes

### 1.0.5

Add explicit end of line for Onscripter-EN ('@','\')

Add the ignore end of line ('_')

Add GPL2 licence text (cuz why not?)

Add a repository line for "vsce package" command to not request it

Add a .gitignore (for NOT publish .vsix by error in the code on Github)

Add a tutorial to package this extension on the REAME.md (this file)

### 1.0.4

Add "exclamcommand" for syntax highlightning

### 1.0.3

Add an icon (very important)

### 1.0.2

Replacement for "Nscripter" to "ONSCripter-EN" on some others places

Add "Dialogue" quote (`) for syntax highlightning

### 1.0.1

Add .utf for syntax detection.

Add "setwindow4" for syntax highlightning

### 1.0.0

Initial release !
