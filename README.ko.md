<p align="center"><img src="assets/logo.png" width="112" alt="SocialExport"></p>
<h1 align="center">SocialExport</h1>
<p align="center">소셜 미디어 데이터를 내보내고 공개 웹 콘텐츠를 Markdown으로 저장하세요.</p>
<p align="center"><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.fr.md">Français</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a></p>
<p align="center"><a href="#download">다운로드</a> · <a href="guide/GUIDE.ko.md">설치 가이드</a> · <a href="https://socialexport.app/en">공식 웹사이트</a></p>

소셜 미디어 분석과 웹 클리핑을 위한 무료 로컬 우선 브라우저 확장 프로그램입니다.

[![SocialExport English homepage](assets/website-overview-en.png)](https://socialexport.app/)

## 내보낼 수 있는 콘텐츠

### 소셜 미디어 데이터

지원 플랫폼의 게시물, 댓글, 작성자 정보, 반응 수치를 CSV로 내보냅니다. CSV를 스프레드시트에서 열어 조사나 보고서에 활용할 수 있습니다. 제공되는 필드는 플랫폼과 페이지 유형에 따라 다릅니다.

#### 다섯 가지 수집 항목

1. **게시물 미디어** — 지원되는 게시물에서 동영상, 오디오, 원본 이미지와 표지를 저장합니다.
2. **게시물 데이터** — ID, URL, 제목, 본문, 작성자, 게시 시간 및 이용 가능한 반응 수를 내보냅니다.
3. **게시물 댓글** — 본문, 작성자, 시간과 지원되는 답글을 내보냅니다.
4. **크리에이터 프로필** — 프로필 URL, 계정명, 소개, 인증 여부와 이용 가능한 팔로워 수를 수집합니다.
5. **크리에이터 게시물 목록** — 프로필이나 지원되는 컬렉션에서 URL, 제목, 날짜 및 제공되는 지표를 정리합니다.

제공되는 항목은 플랫폼과 페이지 유형에 따라 다르며 구조화 데이터는 CSV로 내보낼 수 있습니다.

### 공개 웹 콘텐츠

공개 웹페이지와 게시물을 편집 가능한 Markdown으로 저장하고, 다운로드 가능한 이미지를 ZIP에 담습니다. 제목과 링크를 유지한 편집 가능한 Markdown으로 저장하고, 내려받을 수 있는 이미지는 ZIP에 담을 수 있습니다.

웹 문서와 게시물에서 읽을 수 있는 제목, 링크, 표, 코드 블록과 수식을 유지합니다.

### AI 대화 내보내기

읽을 수 있는 대화나 공유 페이지에서 Markdown을 복사하거나 Markdown 파일 또는 ZIP을 내려받을 수 있습니다. 필요한 경우 원래 서비스에 먼저 로그인하세요.

ChatGPT, Claude, Gemini, Google AI Studio, DeepSeek, Kimi, Doubao, Tencent Yuanbao, Qwen, Zhipu (ChatGLM), Grok, Perplexity.

## 내보내기 대상

소셜 데이터는 CSV, 웹 클립과 AI 대화는 Markdown 또는 ZIP으로 저장합니다. 설정 후 Feishu/Lark의 Base·Docs 또는 Notion 데이터베이스·페이지에 보낼 수 있습니다.

Obsidian URI 모드에서 Markdown 노트를 열 수 있습니다. 이미지를 보관함에 함께 저장하려면 Obsidian Local REST API를 설정하고 이미지 동기화를 켜세요.

## 지원 플랫폼

v0.1.1은 다음 20개 소셜 플랫폼을 지원합니다. 항목과 미디어 지원은 플랫폼과 페이지에 따라 달라집니다.

| | | | |
| --- | --- | --- | --- |
| <img src="assets/platforms/xiaohongshu.webp" width="20" height="20" alt=""> RED (Xiaohongshu) | <img src="assets/platforms/douyin.webp" width="20" height="20" alt=""> Douyin | <img src="assets/platforms/kuaishou.webp" width="20" height="20" alt=""> Kuaishou | <img src="assets/platforms/bilibili.webp" width="20" height="20" alt=""> Bilibili |
| <img src="assets/platforms/weibo.webp" width="20" height="20" alt=""> Weibo | <img src="assets/platforms/zhihu.webp" width="20" height="20" alt=""> Zhihu | <img src="assets/platforms/douban.webp" width="20" height="20" alt=""> Douban | <img src="assets/platforms/okjike.webp" width="20" height="20" alt=""> Jike |
| <img src="assets/platforms/xiaoyuzhou.webp" width="20" height="20" alt=""> Xiaoyuzhou | <img src="assets/platforms/x.webp" width="20" height="20" alt=""> X (Twitter) | <img src="assets/platforms/youtube.webp" width="20" height="20" alt=""> YouTube | <img src="assets/platforms/instagram.webp" width="20" height="20" alt=""> Instagram |
| <img src="assets/platforms/tiktok.webp" width="20" height="20" alt=""> TikTok | <img src="assets/platforms/pinterest.webp" width="20" height="20" alt=""> Pinterest | <img src="assets/platforms/reddit.webp" width="20" height="20" alt=""> Reddit | <img src="assets/platforms/bluesky.webp" width="20" height="20" alt=""> Bluesky |
| <img src="assets/platforms/threads.webp" width="20" height="20" alt=""> Threads | <img src="assets/platforms/facebook.webp" width="20" height="20" alt=""> Facebook | <img src="assets/platforms/linkedin.webp" width="20" height="20" alt=""> LinkedIn | <img src="assets/platforms/substack.webp" width="20" height="20" alt=""> Substack |

## 개인정보와 접근 권한

추출과 로컬 내보내기는 브라우저에서 실행되며 SocialExport 계정이 필요하지 않습니다. 원본 서비스의 접근 권한과 이용 규칙, 저작권 및 개인정보를 존중하세요.

<a id="download"></a>

## 다운로드

최신 버전은 데스크톱 브라우저 8종용 ZIP 4개를 제공합니다. Chromium 계열은 압축 해제된 Manifest V3 확장 프로그램을 지원해야 하며, 서명되지 않은 Firefox 패키지는 재시작 후 다시 불러와야 합니다.

| 브라우저 | ZIP |
| --- | --- |
| Chrome | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chrome.zip) |
| Microsoft Edge | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-edge.zip) |
| Firefox | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-firefox.zip) |
| 360 Extreme, Quark, 360 Secure, Liebao, QQ Browser | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chromium.zip) |

**[SocialExport 공식 웹사이트](https://socialexport.app/)**
