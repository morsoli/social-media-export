<p align="center"><img src="assets/logo.png" width="112" alt="SocialExport"></p>
<h1 align="center">SocialExport 社媒导出助手</h1>
<p align="center"><strong>社媒数据导出与网页剪藏工具</strong><br>导出社媒数据，留存网页内容</p>
<p align="center"><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.fr.md">Français</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a></p>
<p align="center"><a href="#download">下载</a> · <a href="guide/GUIDE.zh-CN.md">安装指南</a> · <a href="https://socialexport.app">官方网站</a></p>

社媒导出助手是一款免费、本地优先的浏览器扩展，适用于社媒研究和网页剪藏。可把结构化数据交给表格分析，也可把可读取的公开内容整理成 Markdown，留作笔记或资料。

[![SocialExport English homepage](assets/website-overview-en.png)](https://socialexport.app/)

## 可以导出什么

### 社媒数据导出

将支持平台的帖子、评论、作者信息和互动数据导出为 CSV。 将可获取的帖子、评论及互动数据交给 Excel 或其他表格工具，用于研究、统计和复盘。字段随平台和页面类型变化。

#### 五个数据采集维度

1. **作品媒体** — 保存支持页面里可获取的视频、音频、原图和封面。
2. **作品数据** — 导出作品 ID、原始链接、标题、正文、作者、发布时间，以及可读取的播放、点赞、收藏、评论和分享数。
3. **作品评论** — 导出评论正文、作者、时间和可读取的互动数据；平台可提供楼中楼时，也可纳入回复。
4. **创作者资料** — 采集主页链接、账号名、个人简介、认证信息，以及可读取的粉丝数、关注数和作品数。
5. **创作者作品** — 从创作者主页或支持的合集整理作品清单，包含作品链接、标题、日期和可读取的互动指标。

可获取的字段和媒体因平台及页面类型而异。媒体保存为文件，结构化数据可导出为 CSV。

### 公开网页剪藏

将公开网页和帖子保存为可编辑的 Markdown，可把可下载图片一起打包为 ZIP。 Markdown 保留可读的正文、标题层级和链接，便于编辑；ZIP 还能打包可获取的图片。

网页剪藏可保留可读取的标题层级、链接、列表、表格、代码块和公式。适用于公开网页、社媒帖子和受支持的文档页面。

### AI 对话导出

打开原站的对话或可读取的分享页，可复制 Markdown，或下载 Markdown 文件及 ZIP。页面要求登录时，先在原站登录。仅能导出浏览器可读取的内容。

ChatGPT, Claude, Gemini, Google AI Studio, DeepSeek, Kimi, Doubao, Tencent Yuanbao, Qwen, Zhipu (ChatGLM), Grok, Perplexity.

## 导出到哪里

社媒结构化数据可下载为 CSV，网页剪藏和 AI 对话可下载为 Markdown 或 ZIP，媒体可单独保存。配置飞书或 Notion 后，社媒数据可写入多维表格或数据库，网页和对话可保存为云文档或页面。

网页剪藏和 AI 对话也可保存到 Obsidian。URI 模式在 Obsidian 打开 Markdown 笔记。需要把可获取的图片一起写入笔记库时，请配置 Obsidian Local REST API，并启用图片同步。

## 平台与兼容性

v0.1.1 覆盖下列 20 个社媒平台。可获取的字段、回复、媒体和功能因平台及页面而异。详见[平台目录](https://socialexport.app/platforms)。

| | | | |
| --- | --- | --- | --- |
| <img src="assets/platforms/xiaohongshu.webp" width="20" height="20" alt=""> 小红书 | <img src="assets/platforms/douyin.webp" width="20" height="20" alt=""> 抖音 | <img src="assets/platforms/kuaishou.webp" width="20" height="20" alt=""> 快手 | <img src="assets/platforms/bilibili.webp" width="20" height="20" alt=""> 哔哩哔哩 |
| <img src="assets/platforms/weibo.webp" width="20" height="20" alt=""> 微博 | <img src="assets/platforms/zhihu.webp" width="20" height="20" alt=""> 知乎 | <img src="assets/platforms/douban.webp" width="20" height="20" alt=""> 豆瓣 | <img src="assets/platforms/okjike.webp" width="20" height="20" alt=""> 即刻 |
| <img src="assets/platforms/xiaoyuzhou.webp" width="20" height="20" alt=""> 小宇宙 | <img src="assets/platforms/x.webp" width="20" height="20" alt=""> X（Twitter） | <img src="assets/platforms/youtube.webp" width="20" height="20" alt=""> YouTube | <img src="assets/platforms/instagram.webp" width="20" height="20" alt=""> Instagram |
| <img src="assets/platforms/tiktok.webp" width="20" height="20" alt=""> TikTok | <img src="assets/platforms/pinterest.webp" width="20" height="20" alt=""> Pinterest | <img src="assets/platforms/reddit.webp" width="20" height="20" alt=""> Reddit | <img src="assets/platforms/bluesky.webp" width="20" height="20" alt=""> Bluesky |
| <img src="assets/platforms/threads.webp" width="20" height="20" alt=""> Threads | <img src="assets/platforms/facebook.webp" width="20" height="20" alt=""> Facebook | <img src="assets/platforms/linkedin.webp" width="20" height="20" alt=""> LinkedIn | <img src="assets/platforms/substack.webp" width="20" height="20" alt=""> Substack |

## 适用场景

- **创作者与社媒运营**：整理作品表现、用户互动和评论反馈。
- **研究与数据分析**：收集公开帖子、评论和创作者信息，在表格工具中分析。
- **资料留存与知识管理**：将公开文章、帖子和可获取的媒体保存到本地、飞书或 Notion。

## 隐私与访问权限

内容解析和本地导出在浏览器内运行，无需注册 SocialExport 账号。发送到飞书或 Notion 时，内容会发往你配置的目标。使用时请遵守原站访问权限、平台规则、版权及隐私要求。

<a id="download"></a>

## 下载

最新版本提供四个 ZIP，覆盖八种桌面浏览器。Chrome 和 Edge 加载解压目录。其余五种 Chromium 浏览器共用安装包，须支持加载解压的 Manifest V3 扩展。Firefox 为未签名临时安装包，重启后需重新加载。

| 浏览器 | ZIP |
| --- | --- |
| Chrome | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chrome.zip) |
| Microsoft Edge | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-edge.zip) |
| Firefox | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-firefox.zip) |
| 360 极速、夸克、360 安全、猎豹和 QQ 浏览器 | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chromium.zip) |

**[打开社媒导出助手官网](https://socialexport.app/)**
