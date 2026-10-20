# 更新日志

[返回首页](README.md) · [功能介绍](FEATURES.md) · [历史版本下载](docs/release-history.md)

这里按版本记录新增、改进和修复。当前功能的完整介绍见“功能介绍”，安装包与校验文件见“历史版本下载”。

## 3.71.1.0 Preview

相对上次公开版本 **3.69.0.0** 的累计更新，完整包含 **3.70.1.0** 的改动。

### 新增与改进

- 清单转移、任务编辑及清单管理在后台处理，等待服务响应时仍可操作其他任务和清单。
- 任务可设置指定日期、每周多个星期几和每天的起止时段，例如每周二、四 17:00–20:00 上课。
- 多清单内容按清单集中排列；在“管理清单”中上移、下移，可调整显示顺序。
- 外观设置支持调整任务圆圈粗细，范围为 0.5–6.0 像素。
- 专注自然结束或手动结束后收起进度环、回到常驻状态；启用完成庆祝时，庆祝结束后恢复常驻。
- 鼠标移出待办侧栏后取消条目视觉高亮，保留右键菜单及键盘操作的目标。

### 修复

- 合入 3.70.1 的慢速回执恢复和重复规则退避重试，改善连接较慢时的同步状态与诊断。
- 等待任务编辑确认后再提交对应重复规则，避免起止时间与规则保存先后顺序不一致。
- 重试已保存任务的重复规则时保持时间设置一致，避免重复提交改变截止时间。

[本版发布页面](https://github.com/fengteng814/nudou-desktop-pet-releases/releases/tag/v3.71.1.0) · [详细发布说明与验证范围](distribution/preview/3.71.1.0/CHANGELOG.md)

## 3.69.0.0 Preview

相对上次公开版本 **3.67.2.0** 的累计更新，包含中间版本 3.68.1.0 的修改：

- 新电脑可在桌宠内输入配对码连接任务服务，无需编辑配置文件；配对成功后自动加载清单。
- 配对码限时使用，支持断线后重试；连接信息加密保存在本机，已有电脑的配对保持不变。
- 家庭网络可直接连接指定 NAS；外网连接需先接入已授权的 Tailscale 网络。
- 管理清单先显示本地缓存，后台自动连接；ToDo 离线提示仅鼠标悬停时显示，保留搜索和未保存设置。
- 编辑待办时可以通过“保存到”转移清单，保留任务编号和完成状态；失败保留草稿。
- 修复檐下听雨抬臂时肩部衣料缺块，并改善亮色高光与蓝色衣料的过渡。

[本版发布页面](https://github.com/fengteng814/nudou-desktop-pet-releases/releases/tag/v3.69.0.0) · [详细发布说明与验证范围](distribution/preview/3.69.0.0/CHANGELOG.md)

## 历史更新日志

按版本从新到旧排列，以下链接保留各次发布时的原始说明：

- [3.67.2.0](distribution/preview/3.67.2.0/CHANGELOG.md)
- [3.66.0.0](distribution/preview/3.66.0.0/CHANGELOG.md)
- [3.62.0.0](distribution/preview/3.62.0.0/CHANGELOG.md)
- [3.61.0.0](distribution/preview/3.61.0.0/CHANGELOG.md)
- [3.60.0.0](distribution/preview/3.60.0.0/CHANGELOG.md)
- [3.58.2.0](distribution/preview/3.58.2.0/CHANGELOG.md)
- [3.58.1.0](distribution/preview/3.58.1.0/CHANGELOG.md)
- [3.57.0.58](distribution/preview/3.57.0.58/CHANGELOG.md)
- [3.57.0.57](distribution/preview/3.57.0.57/CHANGELOG.md)
- [3.57.0.56](distribution/preview/3.57.0.56/CHANGELOG.md)
- [3.57.0.51](distribution/preview/3.57.0.51/CHANGELOG.md)
- [3.57.0.46](distribution/preview/3.57.0.46/CHANGELOG.md)
- [3.57.0.45](distribution/preview/3.57.0.45/CHANGELOG.md)
- [3.57.0.39](distribution/preview/3.57.0.39/CHANGELOG.md)
- [3.57.0.11](distribution/preview/3.57.0.11/CHANGELOG.md)
- [3.57.0.10](distribution/preview/3.57.0.10/CHANGELOG.md)
- [3.57.0.9](distribution/preview/3.57.0.9/CHANGELOG.md)
- [3.57.0.8](distribution/preview/3.57.0.8/CHANGELOG.md)
- [3.57.0.7](distribution/preview/3.57.0.7/CHANGELOG.md)
- [3.57.0.6](distribution/preview/3.57.0.6/CHANGELOG.md)
- [3.57.0.5](distribution/preview/3.57.0.5/CHANGELOG.md)

3.57.0.2 未单独发布 CHANGELOG 文件，可在 [历史版本下载](docs/release-history.md) 中查看其发行文件。
