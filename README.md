# Dev-Cpp Theme for VS Code

如果你之前习惯使用老旧的 Dev-C++ 集成开发环境来编写你的 C++ 代码，现在你依然能够找回你的记忆。本主题尽可能地模拟了 Dev-C++ 的默认配色方案，带你回到过去的时光。

![snapshot](https://s2.ax1x.com/2020/02/24/389TsI.png)

## Install

### Directly import to VS Code

Clone this repository, then copy the whole folder to `~/.vscode/extensions/` . If you are using Windows, `~` represents `%USERPROFILE%` .

### Install from VSIX

Make sure you have npm installed.

```bash
npm install -g vsce
git clone https://github.com/Guyutongxue/DevCppTheme.git
cd DevCppTheme
vsce package
```

The VSIX file will be generated in your working directory. If it failed, please sudo.

### I can't publish it to VS Code Marketplace...

Because I can't apply an Azure developer account without a credit card.