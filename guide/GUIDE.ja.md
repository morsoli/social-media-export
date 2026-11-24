[SocialExport](../README.ja.md) · [GitHub Releases](https://github.com/morsoli/social-media-export/releases/latest)

# インストールガイド

### ダウンロード

| ブラウザー | ZIP |
| --- | --- |
| Chrome | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chrome.zip) |
| Microsoft Edge | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-edge.zip) |
| Firefox | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-firefox.zip) |
| 360 Extreme、Quark、360 Secure、Liebao、QQ Browser | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chromium.zip) |

1. ブラウザーに対応する ZIP を展開します。拡張機能の管理画面でデベロッパーモードを有効にし、`manifest.json` を含むフォルダーを読み込みます。拡張機能メニューから SocialExport を固定できます。
2. Firefox では `about:debugging#/runtime/this-firefox` を開き、**一時的なアドオンを読み込む** を選択して `manifest.json` を指定します。署名されていないため、Firefox の再起動後に読み込み直してください。
3. 対応する SNS 投稿または公開ページを開き、SocialExport を選択します。SNS データは CSV、ウェブページは Markdown ファイルまたは ZIP として保存できます。設定後は Feishu/Lark や Notion に送信できます。

<img src="../assets/chrome-install.png" width="760" alt="SocialExport · Chromium">

| ブラウザー | 拡張機能の管理画面 |
| --- | --- |
| Chrome | `chrome://extensions` |
| Microsoft Edge | `edge://extensions` |
| Firefox | `about:debugging#/runtime/this-firefox` |
| 360 Extreme | 設定 → 拡張機能 |
| Quark | 拡張機能センター → 拡張機能を管理 |
| 360 Secure | 拡張機能 → 管理 → 詳細管理（Windows） |
| Liebao | オプション → マイアプリ（Windows） |
| QQ Browser | 拡張機能 → 拡張機能を管理 |

Chromium 系ブラウザーでは、展開済みフォルダーの読み込みや Manifest V3 への対応がバージョンによって異なります。CRX 専用の画面から ZIP は読み込めません。

<img src="../assets/extension-popup.png" width="480" alt="SocialExport · CSV / Markdown">

[インストールガイド ↗](https://socialexport.app/en/guides/getting-started)
