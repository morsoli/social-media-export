<p align="center"><img src="assets/logo.png" width="112" alt="SocialExport"></p>
<h1 align="center">SocialExport – Social Media Exporter</h1>
<p align="center">Export Social Data. Preserve Web Content.</p>
<p align="center"><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.fr.md">Français</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a></p>
<p align="center"><a href="#download">Downloads</a> · <a href="guide/GUIDE.md">Installation guide</a> · <a href="https://socialexport.app/en">Official website</a></p>

Analyze posts and comments in a spreadsheet, save public webpages as Markdown, or keep an AI conversation for later. SocialExport extracts the content in your browser and lets you choose where the result goes.

[![SocialExport output examples: CSV and Markdown](assets/export-examples-en.webp)](https://socialexport.app/)

## What you can export

### Social media data

Export posts, comments, and creator records as Excel-compatible UTF-8 CSV, or send them to Feishu/Lark Base or a Notion database after configuration.

#### Five collection dimensions

1. **Post media**. Available video (MP4) and audio (MP3) files, original images, covers, Live Photo clips and background music. Image collections can be downloaded as a ZIP.

2. **Post data**. Post ID, platform, type, title, body, available OCR text, link, author name, ID, handle, profile, bio and follower count, collection, hashtags, and publish, update and capture dates. Metrics can include plays, likes, saves, comments and shares. Media columns can include cover, image, Live Photo, video and music URLs, plus duration and IP region where available.

3. **Post comments**. Comment ID and text, author name, ID, handle and profile link, comment and capture times, likes, reply count, IP region and attached image URLs, and source post ID, title and URL. Available replies include their level, parent comment ID and reply target.

4. **Creator profiles**. Creator ID, display name, handle, profile link, bio, verification, avatar link, gender, IP region and capture time, plus available follower, following, post and total interaction counts.

5. **Creator posts**. Post rows from supported profiles or collections, using the post-data fields above. Compare titles, URLs, publishing dates, collections, engagement and available media across a creator’s work.

Available fields and media vary by platform and page type. Media downloads as files; structured data can be exported as CSV.

### Public web content

Save public webpages and posts as editable Markdown or as a ZIP with available images. Clipping preserves readable headings, links, lists, tables, code blocks, and formulas when the page exposes them. It works with readable web articles, social posts, and supported document pages.

### Export AI conversations

Export a readable conversation as Markdown or a ZIP, or copy the Markdown. Open the conversation or a readable share link on its original service. If access requires sign-in, sign in there first. Only content available to the browser can be exported.

| | | | |
| --- | --- | --- | --- |
| <img src="assets/ai-clients/chatgpt.webp" width="22" height="22" alt=""> ChatGPT | <img src="assets/ai-clients/claude.webp" width="22" height="22" alt=""> Claude | <img src="assets/ai-clients/gemini.webp" width="22" height="22" alt=""> Gemini | <img src="assets/ai-clients/aistudio.webp" width="22" height="22" alt=""> Google AI Studio |
| <img src="assets/ai-clients/deepseek.webp" width="22" height="22" alt=""> DeepSeek | <img src="assets/ai-clients/kimi.webp" width="22" height="22" alt=""> Kimi | <img src="assets/ai-clients/doubao.webp" width="22" height="22" alt=""> Doubao | <img src="assets/ai-clients/yuanbao.webp" width="22" height="22" alt=""> Tencent Yuanbao |
| <img src="assets/ai-clients/qwen.webp" width="22" height="22" alt=""> Qwen | <img src="assets/ai-clients/zhipu.webp" width="22" height="22" alt=""> Zhipu (ChatGLM) | <img src="assets/ai-clients/grok.webp" width="22" height="22" alt=""> Grok | <img src="assets/ai-clients/perplexity.webp" width="22" height="22" alt=""> Perplexity |

## Export destinations

Download CSV for social data, Markdown or ZIP for clipped content and AI conversations, and the original media where available. Configure Feishu/Lark or Notion to save social data to a Base table or database, and clips or conversations to Docs or pages.

Save clips and AI conversations to an Obsidian vault. URI mode opens a Markdown note in Obsidian. To save supported images into the vault as well, configure the Obsidian Local REST API and enable image syncing.

## Platforms and compatibility

Check the [platform directory](https://socialexport.app/en/platforms) for the 20 social platforms covered in v0.1.1. Features, fields, replies, and media vary by page and platform.

| | | | |
| --- | --- | --- | --- |
| <img src="assets/platforms/xiaohongshu.webp" width="20" height="20" alt=""> RED (Xiaohongshu) | <img src="assets/platforms/douyin.webp" width="20" height="20" alt=""> Douyin | <img src="assets/platforms/kuaishou.webp" width="20" height="20" alt=""> Kuaishou | <img src="assets/platforms/bilibili.webp" width="20" height="20" alt=""> Bilibili |
| <img src="assets/platforms/weibo.webp" width="20" height="20" alt=""> Weibo | <img src="assets/platforms/zhihu.webp" width="20" height="20" alt=""> Zhihu | <img src="assets/platforms/douban.webp" width="20" height="20" alt=""> Douban | <img src="assets/platforms/okjike.webp" width="20" height="20" alt=""> Jike |
| <img src="assets/platforms/xiaoyuzhou.webp" width="20" height="20" alt=""> Xiaoyuzhou | <img src="assets/platforms/x.webp" width="20" height="20" alt=""> X (Twitter) | <img src="assets/platforms/youtube.webp" width="20" height="20" alt=""> YouTube | <img src="assets/platforms/instagram.webp" width="20" height="20" alt=""> Instagram |
| <img src="assets/platforms/tiktok.webp" width="20" height="20" alt=""> TikTok | <img src="assets/platforms/pinterest.webp" width="20" height="20" alt=""> Pinterest | <img src="assets/platforms/reddit.webp" width="20" height="20" alt=""> Reddit | <img src="assets/platforms/bluesky.webp" width="20" height="20" alt=""> Bluesky |
| <img src="assets/platforms/threads.webp" width="20" height="20" alt=""> Threads | <img src="assets/platforms/facebook.webp" width="20" height="20" alt=""> Facebook | <img src="assets/platforms/linkedin.webp" width="20" height="20" alt=""> LinkedIn | <img src="assets/platforms/substack.webp" width="20" height="20" alt=""> Substack |

## Use cases

- **Social media managers and creators** — Track content performance and review audience feedback.
- **Researchers and data analysts** — Collect posts, comments, and creator activity for spreadsheet analysis.
- **Knowledge management** — Preserve useful articles, posts, and media in local files, Feishu/Lark, or Notion.

## Privacy and access

Extraction and local exports run in the browser without a SocialExport account. Sending content to Feishu/Lark or Notion uses the destination you configure. Respect source-site access requirements, platform rules, copyright, and privacy.

<a id="download"></a>

## Downloads

The latest release provides four ZIPs for eight desktop browsers. Chrome and Edge load unpacked extensions, and the five other Chromium browsers share a package where their browser version supports unpacked Manifest V3. Firefox uses an unsigned temporary add-on that must be loaded again after restarting.

| Browser | ZIP |
| --- | --- |
| Chrome | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chrome.zip) |
| Microsoft Edge | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-edge.zip) |
| Firefox | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-firefox.zip) |
| 360 Extreme, Quark, 360 Secure, Liebao and QQ Browser | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chromium.zip) |

**[Explore SocialExport on the official website](https://socialexport.app/)**
