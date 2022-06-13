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

## Extensions included

### GitHub integration

- GitHub Repositories
- GitHub Pull Requests and Issues
- GitLens

## Python integration

- Python extension
- Pylance
- Pip Manager

## Swift integration (13DTC with Matua Doc)

- Swift
- CodeLLDB

## Web development tools

- HTML CSS Support
- lit-html
- Path Intellisense
- CSS Peek
- Color Info
- Auto Close Tag
- Auto Complete Tag
- Auto Rename Tag
- Live Preview

## General tools

- Indent Rainbow
- Error Lens
- Better Comments
- Docs View
- Markdown All-in-One
- GitHub Markdown Preview
- Markdown Preview Github Styling
- Markdown Checkboxes
- Markdown Emoji
- Markdown Footnotes
- markdownlint
- Draw.io integration
