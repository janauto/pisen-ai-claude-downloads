# 品胜 AI 配置小助手 · Claude 版

## v0.5.6 下载

| 系统 | 安装包 |
| --- | --- |
| Windows 64 位（Intel / AMD） | [下载 Windows x64](https://github.com/janauto/pisen-ai-claude-downloads/raw/refs/heads/main/downloads/v0.5.6/PisenAI-Claude-0.5.6-Windows-amd64.zip) |
| Windows 32 位 | [下载 Windows x86](https://github.com/janauto/pisen-ai-claude-downloads/raw/refs/heads/main/downloads/v0.5.6/PisenAI-Claude-0.5.6-Windows-x86.zip) |
| Windows ARM | [下载 Windows ARM64](https://github.com/janauto/pisen-ai-claude-downloads/raw/refs/heads/main/downloads/v0.5.6/PisenAI-Claude-0.5.6-Windows-arm64.zip) |
| macOS 13 及以上（Apple 芯片 / Intel） | [下载 macOS](https://github.com/janauto/pisen-ai-claude-downloads/raw/refs/heads/main/downloads/v0.5.6/PisenAI-Claude-0.5.6-macOS.zip) |

使用本机 Claude 桌面端时，在助手选择「本机 Claude 桌面端（TUN）」。Windows 完整解压后右键 `PisenAI-Claude.exe`，选择「以管理员身份运行」。macOS 解压后将 `PisenAI-Claude.app` 移到「应用程序」，按系统提示授权 TUN。

更新 Windows 版时，请从系统托盘退出旧版。独立窗口打不开时，右键新版本的托盘图标，选择「用默认浏览器打开界面」。

用管理员发放的员工账号登录。助手加载前置订阅并自动选择节点。两处检测都匹配固定出口 IP 后，点击「打开 Claude 桌面端」。使用固定出口期间保持助手的 TUN 会话开启。

托盘绿勾表示助手的两处固定出口测试已经通过。普通浏览器是否经过固定出口取决于当前连接方式和分流规则。要核对浏览器自身的出口，请在同一个浏览器打开 ipify，并对比实际 IP 与预期 IP。[打开 ipify](https://api.ipify.org)

Windows 包含 Mihomo、分流数据库和 Wintun 0.14.1。Claude 桌面端由 Anthropic 单独提供，按设备选择官方安装包。

[Claude 官方下载](https://claude.com/download) · [SHA-256 校验文件](https://github.com/janauto/pisen-ai-claude-downloads/blob/main/downloads/v0.5.6/SHA256SUMS.txt) · [v0.5.5 下载目录](https://github.com/janauto/pisen-ai-claude-downloads/tree/main/downloads/v0.5.5) · [v0.5.4 下载目录](https://github.com/janauto/pisen-ai-claude-downloads/tree/main/downloads/v0.5.4)

Windows 包附带上游组件许可证。

- [Mihomo v1.19.34 发行和对应源码](https://github.com/MetaCubeX/mihomo/releases/tag/v1.19.34)
- [meta-rules-dat 发行](https://github.com/MetaCubeX/meta-rules-dat/releases)
- [Wintun 官方驱动](https://www.wintun.net/)
