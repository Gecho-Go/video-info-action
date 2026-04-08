# 查看视频信息

macOS Finder 右键快速操作，一秒查看视频分辨率、帧率、编码、时长。

<img width="434" height="135" alt="截屏2026-04-08 10 17 00" src="https://github.com/user-attachments/assets/acbbdc7b-1cf4-4f22-8d53-5c78ac5626e4" />
<img width="450" height="249" alt="截屏2026-04-08 10 14 52" src="https://github.com/user-attachments/assets/e75c9a44-8a84-40fb-9c40-59086d810101" />

## 为什么做这个

macOS 原生的「显示简介」（Cmd+I）不显示帧率。MediaInfo 信息全但界面复杂、全英文。想知道一个视频是 1080p 还是 4K、25fps 还是 60fps，不应该这么麻烦。

这个工具只做一件事：右键视频，立刻看到你最需要的信息。

## 功能

- 📐 分辨率（自动识别横屏/竖屏）
- 🎞 帧率
- 🎬 视频编码
- ⏱ 时长
- 💾 文件大小

## 安装

1. 下载 [查看视频信息.pkg](../../releases/latest)
2. 双击安装，输入管理员密码
3. 右键任意视频文件 → 快速操作 → 查看视频信息

## 设置快捷键（推荐）

设置完成后几乎可以替代原生 Cmd+I，选中视频一个快捷键即可查看信息。

1. 打开**系统设置** → **键盘** → **键盘快捷键**
2. 左侧选择**服务**
3. 在「文件和文件夹」分类下找到**查看视频信息**
4. 双击右侧空白处，按下你想要的快捷键（建议 `Cmd+Shift+M`，不与系统冲突）

## 系统要求

- macOS 13 或更高版本
- Apple Silicon（M 系列芯片）

## 卸载

```bash
sudo rm -rf "/Library/Services/查看视频信息.workflow"
```
