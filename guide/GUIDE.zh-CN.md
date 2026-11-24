[SocialExport](../README.zh-CN.md) · [GitHub Releases](https://github.com/morsoli/social-media-export/releases/latest)

# 安装指南

### 下载

| 浏览器 | ZIP |
| --- | --- |
| Chrome | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chrome.zip) |
| Microsoft Edge | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-edge.zip) |
| Firefox | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-firefox.zip) |
| 360 极速、夸克、360 安全、猎豹和 QQ 浏览器 | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chromium.zip) |

1. 下载对应浏览器的 ZIP 并解压。打开扩展管理，开启开发者模式，加载包含 `manifest.json` 的文件夹，再从扩展菜单固定社媒导出助手。
2. 在 Firefox 打开 `about:debugging#/runtime/this-firefox`，选择 **临时载入附加组件**，再选中 `manifest.json`。未签名测试包需要在重启后重新加载。
3. 打开支持的社媒帖子或公开网页，点击社媒导出助手。可把社媒数据导出为 CSV，把网页保存为 Markdown 文件或 ZIP。配置工作区后，也可发送到飞书 / Lark 或 Notion。

<img src="../assets/chrome-install.png" width="760" alt="SocialExport · Chromium">

| 浏览器 | 扩展管理入口 |
| --- | --- |
| Chrome | `chrome://extensions` |
| Microsoft Edge | `edge://extensions` |
| Firefox | `about:debugging#/runtime/this-firefox` |
| 360 Extreme | 设置 → 扩展程序 |
| Quark | 插件中心 → 插件管理 |
| 360 Secure | 扩展 → 管理 → 高级管理（Windows） |
| Liebao | 选项 → 我的应用（Windows） |
| QQ Browser | 扩展程序 → 管理扩展程序 |

这些桌面 Chromium 浏览器是否支持加载解压目录及 Manifest V3，取决于具体版本。仅接受 CRX 的入口无法加载 ZIP。

<img src="../assets/extension-popup.png" width="480" alt="SocialExport · CSV / Markdown">

[安装指南 ↗](https://socialexport.app/guide)

## 2. 导出通用内容（公开网页与云文档）

1. 打开想保存的公开网页或已打开的飞书云文档（`docx` / `wiki`），等待正文加载完成。
2. 点击工具栏的“社媒导出助手”图标，核对弹窗里显示的标题和域名。
3. 选择 **“导出到 Markdown 压缩包”** 打包正文与可获取的图片资源（`.zip`），或选择 **“导出到 Markdown 文件”** 保存纯文本（`.md`）；配置第三方凭证后也可直接点击 **“导出到飞书”**（保存为飞书云文档）或 **“导出到 Notion”**（保存为 Notion 页面）。

*本地导出不需要配置飞书或 Notion，也不需要注册账号。*

若页面出现图片访问授权提示，只为你准备保存的站点授权。需要登录才可见的内容，应先在原网站正常登录；插件不会代为绕过访问限制。

## 3. 导出社媒平台数据与无水印媒体

1. 打开支持平台的作品详情页或创作者主页。
2. 打开插件弹窗或导出中心，根据识别结果选择 **无水印下载、作品数据、作品评论、创作者数据或创作者作品**；不同平台和页面提供的维度不同。
3. 点击 **“下载无水印”** 保存高清音视频/原图到本地，点击 **“导出到本地”** 生成 Excel 直接可读的 UTF-8 BOM `.csv` 表格，或点击 **“导出到飞书”** / **“导出到 Notion”** 写入在线数据库。

媒体下载支持小红书、抖音、快手、B站、TikTok、YouTube、X、Instagram 和 Pinterest。页面结构、平台策略、登录状态及原始资源质量会影响可提取内容；先使用一条公开链接验证，再进行批量操作。

## 4. 可选：导出到飞书与导出到 Notion

飞书与 Notion 导出是主动选择的第三方直连传输，不是本地导出的前提：

- **导出到飞书**：在插件「设置」中填入个人飞书自建应用凭证（App ID / App Secret）及可选文件夹或多维表格链接，社媒结构化数据会按平台自动写入飞书多维表格并按 ID 去重，通用网页内容会写入飞书云文档。
- **导出到 Notion**：在插件「设置」中填入 Notion Internal Integration Token 与已授权的目标页面或数据库链接，社媒数据会自动写入 Notion 数据库，通用网页内容会生成结构化 Notion 页面。

[查看飞书同步配置指南](https://socialexport.app/blog/feishu-bitable-sync-guide)
