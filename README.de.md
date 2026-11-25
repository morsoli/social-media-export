<p align="center"><img src="assets/logo.png" width="112" alt="SocialExport"></p>
<h1 align="center">SocialExport</h1>
<p align="center">Exportiere Social-Media-Daten und speichere öffentliche Webseiten als Markdown.</p>
<p align="center"><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.fr.md">Français</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a></p>
<p align="center"><a href="#download">Downloads</a> · <a href="guide/GUIDE.de.md">Installationsanleitung</a> · <a href="https://socialexport.app/en">Offizielle Website</a></p>

Eine kostenlose Browser-Erweiterung für Social-Media-Recherche und Web-Clipping mit lokaler Verarbeitung.

[![SocialExport output examples: CSV and Markdown](assets/export-examples-en.webp)](https://socialexport.app/)

## Was sich exportieren lässt

### Social-Media-Daten

Exportiere Beiträge, Kommentare, Angaben zu Profilen und verfügbare Interaktionsdaten als CSV. Öffne CSV-Dateien für Recherche und Berichte in einer Tabellenkalkulation. Welche Felder verfügbar sind, hängt von Plattform und Seitentyp ab.

#### Fünf Erfassungsbereiche

1. **Medien** — Speichere verfügbare Videos, Audiodateien, Originalbilder und Titelbilder.
2. **Beitragsdaten** — Exportiere ID, URL, Titel, Text, Autor, Veröffentlichungsdatum und verfügbare Interaktionswerte.
3. **Kommentare** — Exportiere Text, Autor, Zeitpunkt und verfügbare Antworten.
4. **Creator-Profil** — Erfasse Profil-URL, Nutzernamen, Kurzbiografie, Verifizierung und verfügbare Follower-Zahlen.
5. **Creator-Beiträge** — Erstelle aus einem Profil oder einer unterstützten Sammlung eine Liste mit URLs, Titeln, Datumsangaben und verfügbaren Kennzahlen.

Verfügbare Felder hängen von Plattform und Seitentyp ab. Strukturierte Daten lassen sich als CSV exportieren.

### Öffentliche Webinhalte

Speichere öffentliche Webseiten und Beiträge als bearbeitbares Markdown, auf Wunsch mit verfügbaren Bildern in einer ZIP-Datei. Überschriften, Links und lesbarer Text bleiben im Markdown bearbeitbar. Verfügbare Bilder lassen sich in einer ZIP-Datei bündeln.

Beim Clipping bleiben lesbare Überschriften, Links, Tabellen, Codeblöcke und Formeln aus Seiten und Beiträgen erhalten.

### KI-Unterhaltungen exportieren

Kopiere Markdown oder lade eine Markdown-Datei oder ein ZIP aus einem lesbaren Chat oder Freigabelink herunter. Melde dich bei Bedarf beim ursprünglichen Dienst an.

| | | | |
| --- | --- | --- | --- |
| <img src="assets/ai-clients/chatgpt.webp" width="22" height="22" alt=""> ChatGPT | <img src="assets/ai-clients/claude.webp" width="22" height="22" alt=""> Claude | <img src="assets/ai-clients/gemini.webp" width="22" height="22" alt=""> Gemini | <img src="assets/ai-clients/aistudio.webp" width="22" height="22" alt=""> Google AI Studio |
| <img src="assets/ai-clients/deepseek.webp" width="22" height="22" alt=""> DeepSeek | <img src="assets/ai-clients/kimi.webp" width="22" height="22" alt=""> Kimi | <img src="assets/ai-clients/doubao.webp" width="22" height="22" alt=""> Doubao | <img src="assets/ai-clients/yuanbao.webp" width="22" height="22" alt=""> Tencent Yuanbao |
| <img src="assets/ai-clients/qwen.webp" width="22" height="22" alt=""> Qwen | <img src="assets/ai-clients/zhipu.webp" width="22" height="22" alt=""> Zhipu (ChatGLM) | <img src="assets/ai-clients/grok.webp" width="22" height="22" alt=""> Grok | <img src="assets/ai-clients/perplexity.webp" width="22" height="22" alt=""> Perplexity |

## Exportziele

Speichere Social-Media-Daten als CSV und Clips oder KI-Unterhaltungen als Markdown oder ZIP. Nach der Einrichtung lassen sie sich in Feishu/Lark Base oder Docs bzw. in Notion-Datenbanken oder -Seiten speichern.

Der URI-Modus öffnet eine Markdown-Notiz in Obsidian. Für Bilder im Tresor richte die Obsidian Local REST API ein und aktiviere die Bildsynchronisierung.

## Plattformen und Kompatibilität

Version 0.1.1 deckt die folgenden 20 Plattformen ab. Verfügbare Felder und Medien hängen von der Seite und Plattform ab.

| | | | |
| --- | --- | --- | --- |
| <img src="assets/platforms/xiaohongshu.webp" width="20" height="20" alt=""> RED (Xiaohongshu) | <img src="assets/platforms/douyin.webp" width="20" height="20" alt=""> Douyin | <img src="assets/platforms/kuaishou.webp" width="20" height="20" alt=""> Kuaishou | <img src="assets/platforms/bilibili.webp" width="20" height="20" alt=""> Bilibili |
| <img src="assets/platforms/weibo.webp" width="20" height="20" alt=""> Weibo | <img src="assets/platforms/zhihu.webp" width="20" height="20" alt=""> Zhihu | <img src="assets/platforms/douban.webp" width="20" height="20" alt=""> Douban | <img src="assets/platforms/okjike.webp" width="20" height="20" alt=""> Jike |
| <img src="assets/platforms/xiaoyuzhou.webp" width="20" height="20" alt=""> Xiaoyuzhou | <img src="assets/platforms/x.webp" width="20" height="20" alt=""> X (Twitter) | <img src="assets/platforms/youtube.webp" width="20" height="20" alt=""> YouTube | <img src="assets/platforms/instagram.webp" width="20" height="20" alt=""> Instagram |
| <img src="assets/platforms/tiktok.webp" width="20" height="20" alt=""> TikTok | <img src="assets/platforms/pinterest.webp" width="20" height="20" alt=""> Pinterest | <img src="assets/platforms/reddit.webp" width="20" height="20" alt=""> Reddit | <img src="assets/platforms/bluesky.webp" width="20" height="20" alt=""> Bluesky |
| <img src="assets/platforms/threads.webp" width="20" height="20" alt=""> Threads | <img src="assets/platforms/facebook.webp" width="20" height="20" alt=""> Facebook | <img src="assets/platforms/linkedin.webp" width="20" height="20" alt=""> LinkedIn | <img src="assets/platforms/substack.webp" width="20" height="20" alt=""> Substack |

## Datenschutz und Zugriff

Extraktion und lokaler Export laufen ohne SocialExport-Konto im Browser. Beachte Zugriffsrechte, Plattformregeln, Urheberrecht und Datenschutz.

<a id="download"></a>

## Downloads

Die aktuelle Version bietet vier ZIP-Dateien für acht Desktop-Browser. Chromium-Browser müssen entpackte Manifest-V3-Erweiterungen laden können. Das unsignierte Firefox-Add-on muss nach einem Neustart erneut geladen werden.

| Browser | ZIP |
| --- | --- |
| Chrome | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chrome.zip) |
| Microsoft Edge | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-edge.zip) |
| Firefox | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-firefox.zip) |
| 360 Extreme, Quark, 360 Secure, Liebao und QQ Browser | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chromium.zip) |

**[SocialExport auf der offiziellen Website entdecken](https://socialexport.app/)**
