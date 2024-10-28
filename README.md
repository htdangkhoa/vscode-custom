# vscode-custom

## Prerequisites

- Extension: [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)

## Usage

- Press <kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (for Mac) or <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (for Windows or Linux), select `Open User Settings (JSON)`
- Add this, replace username and save
  ```json
  {
    ...
    "vscode_custom_css.imports": [
      "file:///Users/<username>/vscode/custom-vs-code.css",
      "file:///Users/<username>/vscode/custom-vs-code.js",
    ]
  }
  ```
- Press <kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (for Mac) or <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (for Windows or Linux), select `Reload Custom CSS and JS`

## Images

![image](https://github.com/user-attachments/assets/8831a5e4-6203-445b-8f08-c47507f009e7)

## Ref:

https://rudreshoza98.hashnode.dev/unlocking-power-of-vscode-for-your-workflow
