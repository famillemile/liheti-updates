# LIHETI MANAGER CLIENT

Téléchargements corrigés du **16 novembre 2026** : [page officielle](https://famillemile.github.io/liheti-updates/) · [release](https://github.com/famillemile/liheti-updates/releases/tag/v3.12.62-client-portail-zoom.20261116).

| Plateforme | Fichier |
| --- | --- |
| Android CLIENT 3.12.62.37 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-portail-zoom.20261116/LIHETI-GV1-CLIENT-3.12.62.37-PORTAIL-ZOOM-20261116.apk) |
| Windows CLIENT — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-portail-zoom.20261116/LIHETI-GV1-CLIENT-Setup-3.12.62-PORTAIL-ZOOM-20261116.exe) |
| Linux CLIENT — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-portail-zoom.20261116/LIHETI-GV1-CLIENT-3.12.62-PORTAIL-ZOOM-20261116-x86_64.AppImage) |
| Ubuntu / Debian CLIENT — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-portail-zoom.20261116/LIHETI-GV1-CLIENT-3.12.62-PORTAIL-ZOOM-20261116-amd64.deb) |
| macOS Intel — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-portail-zoom.20261116/LIHETI-GV1-CLIENT-3.12.62-PORTAIL-ZOOM-20261116-x64.zip) |
| macOS Apple Silicon — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-portail-zoom.20261116/LIHETI-GV1-CLIENT-3.12.62-PORTAIL-ZOOM-20261116-arm64.zip) |

Portail, coordonnées Mobile Money du serveur actif, opérateurs régionaux, tarifs STANDARD, durées écrites en entier et zoom PC corrigés. Les valeurs initiales restent modifiables. Les installateurs incluent le même moteur CLIENT vérifié.

Tests : `npm run check`, preflight CLIENT et tests de production réussis ; validation GitHub réussie dans le dépôt source privé. Essais à chaud Ubuntu et Windows. Android **.36 → .37** installé dans Waydroid sur Ubuntu sans désinstallation ; navigation tactile et aperçu des trois modèles vérifiés à **320, 390 et 412 px**, sans débordement horizontal. Les données locales contrôlées et les réglages du portail sont conservés.

Android : **3.12.62.37**, certificat SHA-256 **000d5cadff59ad8f5228abcf663c1fc20533bb78fb645ac062394e9b30c1a2cc**. Cette empreinte corrige l’ancienne information publiée pour .36 ; les fichiers .36 et .37 utilisent bien ce même certificat. Certaines anciennes versions portent un autre certificat et demandent une migration avec sauvegarde ; ne pas les désinstaller automatiquement.

La version de base PC reste 3.12.62 : installez le nouveau fichier daté du 16 novembre pour recevoir ces correctifs. Les anciens téléchargements restent dans l’historique des releases.

Limites : macOS Intel/Apple Silicon non signés et non notarisés, sans essai sur Mac réel. Téléphone physique, paiement réel et parcours Hotspot jusqu’à expiration restent à valider. Les essais réseau ne certifient pas tous les modèles des cinq constructeurs. Les limites précédemment signalées pour WireGuard/BTH et le VPN Waydroid ne sont pas levées par cette mise à jour.

Vérification : [SHA256SUMS-CLIENT.txt](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-portail-zoom.20261116/SHA256SUMS-CLIENT.txt). Windows sans Authenticode ; Linux sans signature GPG. Sauvegardez la base LIHETI avant mise à jour.
