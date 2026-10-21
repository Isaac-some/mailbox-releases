# 邮箱助手 v2.4.1 下载

无需 GitHub 登录或仓库权限，公开直接下载：

- [Windows x64 ZIP](https://github.com/Isaac-some/mailbox-releases/releases/download/v2.4.1/MailAssistant-Windows-x64-v2.4.1.zip)：完整解压后打开“邮箱助手.exe”，保留同目录 server 文件夹。
- [macOS Apple Silicon DMG](https://github.com/Isaac-some/mailbox-releases/releases/download/v2.4.1/MailAssistant-AppleSilicon-v2.4.1.dmg)：M 系列芯片、macOS 15+。拖到“应用程序”后打开。

[版本说明与 SHA-256 校验文件](https://github.com/Isaac-some/mailbox-releases/releases/tag/v2.4.1)

本版优化邮箱连接提示，明确提醒 VPN/代理节点可能无法连接邮箱域名的收发端口，并建议切换节点。

v2.4.0 用户可直接在应用内更新：Mac 从“邮箱助手 → 检查更新…”进入；Windows 点击顶部“检查更新”；也可打开“本机数据 → 检查更新”。账号、邮件、密钥和设置会保留。v2.3.9 及之前版本需要手动安装本版一次。

已通过 819 项回归及 Mac、Windows 从 v2.4.0 实际自动升级、损坏包拦截、安装失败回退和任务阻止重启验证。[双平台升级验收](https://github.com/Isaac-some/mailbox/actions/runs/39588860915)。

VPN 请使用覆盖 GitHub 的节点或全局模式，确保 github.com 与 release-assets.githubusercontent.com 可访问。

本仓库仅提供安装包、校验信息及使用说明，不提供租户授权源文件。公开二进制中的内置授权仍可被分析和提取；编译不是保密机制。macOS 为本地签名，尚未经过 Apple 公证。
