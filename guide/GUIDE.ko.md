[SocialExport](../README.ko.md) · [GitHub Releases](https://github.com/morsoli/social-media-export/releases/latest)

# 설치 가이드

### 다운로드

| 브라우저 | ZIP |
| --- | --- |
| Chrome | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chrome.zip) |
| Microsoft Edge | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-edge.zip) |
| Firefox | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-firefox.zip) |
| 360 Extreme, Quark, 360 Secure, Liebao, QQ Browser | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chromium.zip) |

1. 브라우저에 맞는 ZIP을 내려받아 압축을 풉니다. 확장 프로그램 관리 페이지에서 개발자 모드를 켜고 `manifest.json`이 들어 있는 폴더를 불러옵니다. 확장 메뉴에서 SocialExport를 고정할 수 있습니다.
2. Firefox에서는 `about:debugging#/runtime/this-firefox`를 열고 **임시 부가 기능 로드**를 선택한 뒤 `manifest.json`을 지정합니다. 서명되지 않은 패키지는 Firefox를 다시 시작한 후 불러와야 합니다.
3. 지원되는 소셜 게시물이나 공개 페이지를 열고 SocialExport를 선택합니다. 소셜 데이터는 CSV로, 웹페이지는 Markdown 파일이나 ZIP으로 저장할 수 있습니다. 연결을 설정하면 Feishu/Lark 또는 Notion으로 보낼 수 있습니다.

<img src="../assets/chrome-install.png" width="760" alt="SocialExport · Chromium">

| 브라우저 | 확장 관리 위치 |
| --- | --- |
| Chrome | `chrome://extensions` |
| Microsoft Edge | `edge://extensions` |
| Firefox | `about:debugging#/runtime/this-firefox` |
| 360 Extreme | 설정 → 확장 프로그램 |
| Quark | 확장 센터 → 확장 관리 |
| 360 Secure | 확장 프로그램 → 관리 → 고급 관리(Windows) |
| Liebao | 옵션 → 내 앱(Windows) |
| QQ Browser | 확장 프로그램 → 확장 관리 |

Chromium 계열 브라우저의 Manifest V3 지원과 압축 해제 폴더 설치 가능 여부는 버전에 따라 다릅니다. CRX 전용 메뉴에서는 ZIP을 설치할 수 없습니다.

<img src="../assets/extension-popup.png" width="480" alt="SocialExport · CSV / Markdown">

[설치 가이드 ↗](https://socialmediaexport.liduos.com/en/guide)
