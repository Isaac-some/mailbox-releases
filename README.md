# 邮箱助手 v2.4.0 下载

无需 GitHub 登录或仓库权限，公开直接下载：

- [Windows x64 ZIP](https://github.com/Isaac-some/mailbox-releases/releases/download/v2.4.0/MailAssistant-Windows-x64-v2.4.0.zip)：完整解压后打开“邮箱助手.exe”，保留同目录 server 文件夹。
- [macOS Apple Silicon DMG](https://github.com/Isaac-some/mailbox-releases/releases/download/v2.4.0/MailAssistant-AppleSilicon-v2.4.0.dmg)：M 系列芯片、macOS 15+。拖到“应用程序”后打开。

[版本说明与 SHA-256 校验文件](https://github.com/Isaac-some/mailbox-releases/releases/tag/v2.4.0)

本版新增应用内检查、下载及重启更新。Mac 从“邮箱助手 → 检查更新…”进入；Windows 点击顶部“检查更新”；也可打开“本机数据 → 检查更新”。账号、邮件、密钥和设置会保留。旧版用户需要手动安装本版一次，之后即可在应用内更新。

已通过 819 项回归及 Mac、Windows 实际公开下载、自动升级、损坏拦截、失败回退和任务阻止重启验证。[双平台升级验收](https://github.com/Isaac-some/mailbox/actions/runs/39560392608)，[最终安装包验证](https://github.com/Isaac-some/mailbox/actions/runs/39559639764)。

VPN 请使用覆盖 GitHub 的节点或全局模式，确保 github.com 与 release-assets.githubusercontent.com 可访问。

本仓库仅提供安装包、校验信息及使用说明，不提供租户授权源文件。公开二进制中的内置授权仍可被分析和提取；编译不是保密机制。macOS 为本地签名，尚未经过 Apple 公证。
