# 安装与更新

## 首次安装

1. 从 [最新版本页面](https://github.com/fengteng814/nudou-desktop-pet-releases/releases/tag/v3.69.0.0) 下载 `NudouDesktopPet-3.69.0.0-preview-setup.exe`。
2. 双击安装包，核对版本与安装位置，按提示确认安装。
3. 启动努豆。需要同步待办时，按照 [任务服务配对说明](task-service.md) 连接服务器。

程序使用 Windows .NET Framework 4.8。新旧安装包都应从本仓库获取。

## 更新已有桌宠

桌宠右键 → 设置 → 检查更新。也可下载上述 EXE，选择现有安装目录进行更新。

安装器会正常退出旧程序并备份，再更新程序文件；保留已有设置、笔记和独立配对配置。安装后以实际启动的版本为准。

较早的脚本安装版本如果不能接收原生 EXE 更新，请手动下载 EXE 安装包升级一次。

## 便携版

下载 [便携 ZIP](https://github.com/fengteng814/nudou-desktop-pet-releases/releases/download/v3.69.0.0/NudouDesktopPet-3.69.0.0-Extract-And-Run.zip) 并完整解压，再运行其中的“努豆桌宠.exe”。便携 ZIP 是解压运行包；升级现有安装时推荐使用安装器，以保留备份与回退流程。

## 校验与回退

[SHA256SUMS.txt](https://github.com/fengteng814/nudou-desktop-pet-releases/releases/download/v3.69.0.0/SHA256SUMS.txt) 列出了安装包与便携 ZIP 的 SHA256。Windows 可用 `Get-FileHash -Algorithm SHA256` 计算文件哈希并核对。

需要回退时，优先使用安装器高级选项中的“回退上一版”；历史安装包见 [版本索引](release-history.md)。保留现有用户数据，不要用旧配置覆盖新数据。
