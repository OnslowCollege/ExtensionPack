# Onslow College

![Onslow College Logo](img/onslow.png)

This extension pack contains all of the packages necessary for Digital Technologies at [Onslow College](https://www.onslow.school.nz/).

## Setup

1. Install this extension pack.
2. Show the Command Palette (View menu → Command Palette, or (Ctrl/Cmd)-Shift-P
3. Type "user settings", then select User Settings (JSON)
4. Copy-paste the following settings into the JSON

```json
"python.linting.enabled": true,
"python.linting.pycodestyleEnabled": true,
"python.linting.pydocstyleEnabled": true,
"python.linting.pydocstyleArgs": [
    "--convention=pep257"
],
"python.linting.mypyEnabled": true,
"python.linting.mypyArgs": [
    "--strict",
    "--follow-imports=silent",
    "--ignore-missing-imports",
    "--show-column-numbers",
    "--pretty"
],
"editor.wordWrap": "on",
"editor.fontSize": 16,
"editor.formatOnSave": true,
"editor.formatOnSaveMode": "modificationsIfAvailable",
"editor.formatOnType": true
```
