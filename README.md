# 🦝 Checkly VS Code Extension

Run your local Playwright/Puppeteer E2E tests through your Checkly Account directly from VS Code!

## 📱 Features

- Adds a `🦝 Run in Checkly` button and command to VS Code
- Will report the adhoc test result directly via a VS Code notification

## 📌 Installation

- Download the `.vsix` file from the latest [Github Release](https://github.com/ndom91/checkly-vscode/releases) and [install it manually](https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix)

## 🏗️ Usage

1. You must have a valid Checkly check open in VS Code, with a filename like `*.check.js`
2. When attempting to start an adhoc check run for the first time, it will ask you for two config options:
   1. A Checkly `accountId`
   2. A Checkly Bearer Token which you can get from the headers of any authenticated Fetch/XHR request in the web app
3. Then there are two ways to initiate a check run:
   1. You can use the `🦝 Run Current File` button in the bottom status bar in VS Code
   2. The command palette command `Checkly: Run Current File`

## 🏋️‍♀️ Contributing

We're open to most contributions, please stick to the [contributing guidelines]() and formatting settings!

### Todo

- Report logs of failed tests
- Allow customising check run location

## 📝 License

MIT
