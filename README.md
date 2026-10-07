# 获客 客户端

首次使用需要激活码，向实施老师索取。

## Mac

打开「终端」，粘贴这一行，回车：

```
curl -fsSL https://github.com/NovastrumLab/huoke-releases/releases/latest/download/install.sh | bash
```

装好后会自动打开。以后在「启动台」里点「获客」就行。

也可以在 [Releases](https://github.com/NovastrumLab/huoke-releases/releases/latest) 里下载 `.dmg`，拖进「应用程序」。苹果芯片的 Mac 下载 `arm64`，Intel 芯片的下载 `x64`。这样装完第一次打开会被系统拦下，提示无法验证开发者，需要在终端里再跑一行：

```
xattr -dr com.apple.quarantine /Applications/获客.app
```

上面那条命令行安装不会遇到这个问题。

## Windows

需要 64 位的 Windows 10 或 Windows 11。

1. 在 [Releases](https://github.com/NovastrumLab/huoke-releases/releases/latest) 里下载 `.exe`。浏览器如果提示这个文件不常见，选择「保留」。
2. 双击安装。Windows 如果弹出「Windows 已保护你的电脑」，先点「更多信息」，再点「仍要运行」。
3. 装好后在开始菜单里点「获客」。

以后有新版本，软件会在「设置」里提示更新。

## 遇到问题

装不上或者打不开，联系实施老师。
