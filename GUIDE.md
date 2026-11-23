[SocialExport](README.md) · [GitHub Releases](https://github.com/morsoli/social-media-export/releases/latest)

# Installation guide

### Downloads

| Browser | ZIP |
| --- | --- |
| Chrome | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chrome.zip) |
| Microsoft Edge | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-edge.zip) |
| Firefox | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-firefox.zip) |
| 360 Extreme, Quark, 360 Secure, Liebao and QQ Browser | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chromium.zip) |

1. Download the ZIP for your browser and extract it. Open the extension manager, enable developer mode, and load the folder containing `manifest.json`. Pin SocialExport from the extensions menu.
2. In Firefox, open `about:debugging#/runtime/this-firefox`, choose **Load Temporary Add-on**, and select `manifest.json`. The unsigned package must be reloaded after Firefox restarts.
3. Open a supported social post or a public page, then select SocialExport. Export available social data as CSV, or save a page as a Markdown file or ZIP. You can also send content to Feishu/Lark or Notion after connecting your workspace.

<img src="assets/chrome-install.png" width="760" alt="SocialExport · Chromium">

| Browser | Where to open extensions |
| --- | --- |
| Chrome | `chrome://extensions` |
| Microsoft Edge | `edge://extensions` |
| Firefox | `about:debugging#/runtime/this-firefox` |
| 360 Extreme | Settings → Extensions |
| Quark | Extension center → Manage extensions |
| 360 Secure | Extensions → Manage → Advanced management (Windows) |
| Liebao | Options → My apps (Windows) |
| QQ Browser | Extensions → Manage extensions |

On these desktop Chromium browsers, unpacked installation and Manifest V3 support depend on the browser version. Versions that only accept CRX cannot load the ZIP through that entry.

<img src="assets/extension-popup.png" width="480" alt="SocialExport · CSV / Markdown">

[Installation guide ↗](https://socialmediaexport.liduos.com/en/guide)

## 2. Export generic web & document content

1. Open any public web page or open Feishu cloud doc (`docx` / `wiki`) and wait for its content to load.
2. Select the SocialExport toolbar icon and check the displayed page title and domain.
3. Select **Export to Markdown ZIP** for the full document plus offline image assets, or **Export to Markdown File** for a standalone `.md` file; once configured, you can also select **Export to Feishu** (Feishu Docs) or **Export to Notion** (Notion Pages).

*Local export does not require a Feishu/Notion integration or a product account.*

Grant image access only for sites you intend to save. Sign in on the original site if necessary; the extension does not bypass access restrictions.

## 3. Export social media data & watermark-free media

1. Open a supported post or creator profile.
2. Open the extension popup or Export Center and choose an available **Watermark-Free Media**, **Post Data**, **Post Comments**, **Creator Profile**, or **Creator Works** entry. Available dimensions vary by platform and page.
3. Select **Download Watermark-Free** to save HD media, **Export Locally** to download a UTF-8 BOM `.csv` spreadsheet, or **Export to Feishu** / **Export to Notion** to write directly to your online database.

Media extraction supports Xiaohongshu, Douyin, Kuaishou, Bilibili, TikTok, YouTube, X, Instagram and Pinterest. Availability depends on platform policies, page structure, session state and source quality. Verify one public item before starting a batch.

## 4. Optional: Export to Feishu & Export to Notion

Cloud export is an intentional browser-to-API transfer, not a prerequisite for local export:

- **Export to Feishu**: Configure your own Feishu / Lark app credentials (`App ID` / `App Secret`) and optional folder or Base URL in extension settings to export social data to Feishu Base tables and web content to Feishu Docs.
- **Export to Notion**: Configure your Notion Internal Integration Token and shared parent page or database URL in extension settings to export social data to Notion Databases and web content to structured Notion Pages.

[Read the Feishu configuration guide](/en/blog/feishu-bitable-sync-guide)
