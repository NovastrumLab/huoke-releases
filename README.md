# 获客

激活需要激活码。若没有，请联系实施老师。

## Mac

打开“终端”，粘贴以下命令并按回车：

```
curl -fsSL https://github.com/NovastrumLab/huoke-releases/releases/latest/download/install.sh | bash
```

安装完成后，获客会自动打开。之后可从“启动台”打开。

也可以在 [Releases](https://github.com/NovastrumLab/huoke-releases/releases/latest) 下载 `.dmg`，将获客拖入“应用程序”。Apple 芯片的 Mac 选择 `arm64`，Intel 芯片的选择 `x64`。用这种方式安装后，首次打开会被系统阻止，需要在“终端”中运行：

```
xattr -dr com.apple.quarantine /Applications/获客.app
```

## Windows

需要64位的 Windows 10 或 Windows 11。

1. 在 [Releases](https://github.com/NovastrumLab/huoke-releases/releases/latest) 下载 `.exe`。若浏览器提示此文件不常见，选择“保留”。
2. 打开下载的文件。若出现“Windows 已保护你的电脑”，点按“更多信息”，然后点按“仍要运行”。
3. 安装完成后，从“开始”菜单打开获客。

## 更新

有新版本时，获客会在“设置”中显示更新。

## 需要帮助

无法安装或无法打开时，请联系实施老师。
