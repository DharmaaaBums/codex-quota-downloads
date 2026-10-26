# Codex 哨站 · 轻量版

macOS 菜单栏额度监控工具，支持 Codex、MiniMax、DeepSeek 和自定义额度接口。

**[⬇ 下载 v2.6.0 安装镜像（DMG，约1.4 MB）](https://github.com/DharmaaaBums/codex-quota-downloads/releases/download/v2.6.0/CodexQuota-2.6.0-lite-macOS-universal2.dmg)**

[备用 ZIP 下载](https://github.com/DharmaaaBums/codex-quota-downloads/releases/download/v2.6.0/CodexQuota-2.6.0-lite-macOS-universal2.zip) · [最新版本与全部附件](https://github.com/DharmaaaBums/codex-quota-downloads/releases/latest)

## 安装与连接

1. 先退出旧版。打开 DMG，将「Codex 哨站.app」拖入 Applications（应用程序）。
2. 从“应用程序”启动，点击屏幕顶部菜单栏图标。
3. **Codex**：点击“连接 Codex”。无需提前安装 Codex；首次按需下载约100–110 MB官方原生组件，随后在浏览器登录自己的ChatGPT账号，完成后自动读取额度。已有登录可直接使用。
4. **MiniMax**：使用套餐Subscription Key连接，或识别Claude Code中的官方MiniMax配置。普通按量密钥与套餐密钥不通用。
5. **DeepSeek**：点击“＋服务→DeepSeek”，填写一次API密钥，即可自动读取余额。已有官方DeepSeek配置可自动识别。其他平台可配置公开HTTPS额度接口；没有公开查询接口的平台不支持自动读取。

支持macOS 13及以上，兼容Apple Silicon与Intel。无需安装Python、Xcode或Homebrew。首次组件准备需要访问官方GitHub。

## v2.6.0 更新

修复Codex登录链接字段不匹配、轻量版缺少组件时点击无反馈的问题；新增可取消的官方组件准备流程、连接错误提示、登录与配置变更后的自动刷新，以及DeepSeek余额预设。

## 签名与隐私

当前应用为临时签名，尚未经过Apple公证。首次下载后如被系统拦截，请在确认来源可信后按“系统设置→隐私与安全性”中的提示打开。

本仓库仅发布轻量版安装包、使用说明和校验表。安装包不含开发者账号、API密钥、登录资料或产品源码；密钥由使用者自己配置并保存在系统钥匙串。组件仅从官方来源下载并验证SHA-256及上游签名。

**请使用上面的DMG/ZIP链接。绿色Code菜单中的Download ZIP及Releases里的Source code只包含本下载仓库的说明文件，不是应用安装包。**

发布页中的SHA256SUMS.txt可验证DMG、ZIP和中文说明。历史版本仅作留档，推荐使用v2.6.0。
