# 获客 客户端

Mac 上打开「终端」，粘贴这一行，回车：

```
curl -fsSL https://github.com/NovastrumLab/huoke-releases/releases/latest/download/install.sh | bash
```

装好后会自动打开。以后在「启动台」里点「获客」就行。

首次使用需要激活码，向实施老师索取。

## 手动安装

也可以在 [Releases](https://github.com/NovastrumLab/huoke-releases/releases/latest) 里下载 `.dmg`，
拖进「应用程序」。这样装完第一次打开会被系统拦下，提示无法验证开发者，需要在终端里再跑一行：

```
xattr -dr com.apple.quarantine /Applications/获客.app
```

上面那条命令行安装不会遇到这个问题。

## 遇到问题

装不上或者打不开，联系实施老师。
