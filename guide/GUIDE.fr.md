[SocialExport](../README.fr.md) · [GitHub Releases](https://github.com/morsoli/social-media-export/releases/latest)

# Guide d’installation

### Téléchargements

| Navigateur | ZIP |
| --- | --- |
| Chrome | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chrome.zip) |
| Microsoft Edge | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-edge.zip) |
| Firefox | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-firefox.zip) |
| 360 Extreme, Quark, 360 Secure, Liebao et QQ Browser | [ZIP](https://github.com/morsoli/social-media-export/releases/latest/download/social-export-chromium.zip) |

1. Téléchargez puis extrayez le ZIP correspondant à votre navigateur. Activez le mode développeur dans le gestionnaire d’extensions et chargez le dossier contenant `manifest.json`. Épinglez SocialExport depuis le menu des extensions.
2. Dans Firefox, ouvrez `about:debugging#/runtime/this-firefox`, choisissez **Charger un module complémentaire temporaire**, puis sélectionnez `manifest.json`. Rechargez le paquet non signé après chaque redémarrage de Firefox.
3. Ouvrez une publication compatible ou une page publique et sélectionnez SocialExport. Exportez les données sociales en CSV ou enregistrez la page en Markdown ou en ZIP. Après configuration, vous pouvez envoyer le contenu vers Feishu/Lark ou Notion.

<img src="../assets/chrome-install.png" width="760" alt="SocialExport · Chromium">

| Navigateur | Gestionnaire d’extensions |
| --- | --- |
| Chrome | `chrome://extensions` |
| Microsoft Edge | `edge://extensions` |
| Firefox | `about:debugging#/runtime/this-firefox` |
| 360 Extreme | Paramètres → Extensions |
| Quark | Centre d’extensions → Gérer les extensions |
| 360 Secure | Extensions → Gérer → Gestion avancée (Windows) |
| Liebao | Options → Mes applications (Windows) |
| QQ Browser | Extensions → Gérer les extensions |

Le chargement d’un dossier décompressé et la prise en charge de Manifest V3 dépendent de la version du navigateur. Une option réservée aux fichiers CRX ne permet pas de charger le ZIP.

<img src="../assets/extension-popup.png" width="480" alt="SocialExport · CSV / Markdown">

[Guide d’installation ↗](https://socialexport.app/en/guide)
