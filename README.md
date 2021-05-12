# Dev-Cpp Theme for VS Code

如果你之前习惯使用老旧的 Dev-C++ 集成开发环境来编写你的 C++ 代码，现在你依然能够找回你的记忆。本主题尽可能地模拟了 Dev-C++ 的默认配色方案，带你回到过去的时光。[安装地址](https://marketplace.visualstudio.com/items?itemName=Guyutongxue.devcpp-theme)。

![snapshot](https://s1.ax1x.com/2020/05/21/YHxrAe.png)

## Issues won't be fixed now

- C++20 keywords are not highlighted, like `constinit`, `consteval`, etc.
- Tokens `...` are not highlighted correctly.
- Keywords `char16_t`, `char32_t` are not highlighted.
- Expression `sizeof a` cannot be highlighted correctly.
- The highlighting in preprocessor direcives is a mess.
- The return type of Lambda Expressions are not highlighted.

## Install

Just click [Here](https://marketplace.visualstudio.com/items?itemName=Guyutongxue.devcpp-theme) to install through VS Marketplace.

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

## Contribution

If you have any idea of improving this theme, just feel free to make a issue or pull request.