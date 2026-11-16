# LIHETI MANAGER CLIENT

Téléchargements corrigés du **16 novembre 2026 — connexions IP** : [page officielle](https://famillemile.github.io/liheti-updates/) · [release](https://github.com/famillemile/liheti-updates/releases/tag/v3.12.62-client-connexion-ip.20261116).

| Plateforme | Fichier |
| --- | --- |
| Android CLIENT 3.12.62.39 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexion-ip.20261116/LIHETI-GV1-CLIENT-3.12.62.39-CONNEXION-IP-20261116.apk) |
| Windows CLIENT — connexion IP — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexion-ip.20261116/LIHETI-GV1-CLIENT-Setup-3.12.62-CONNEXION-IP-20261116.exe) |
| Linux CLIENT — connexion IP — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexion-ip.20261116/LIHETI-GV1-CLIENT-3.12.62-CONNEXION-IP-20261116-x86_64.AppImage) |
| Ubuntu / Debian CLIENT — connexion IP — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexion-ip.20261116/LIHETI-GV1-CLIENT-3.12.62-CONNEXION-IP-20261116-amd64.deb) |
| macOS Intel — connexion IP — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexion-ip.20261116/LIHETI-GV1-CLIENT-3.12.62-CONNEXION-IP-20261116-x64.zip) |
| macOS Apple Silicon — connexion IP — 16/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexion-ip.20261116/LIHETI-GV1-CLIENT-3.12.62-CONNEXION-IP-20261116-arm64.zip) |

Une adresse IP modifiée reste enregistrée ; un test ancien ne peut plus la rétablir. « Utiliser » reste limité au serveur choisi. Le dernier serveur possède désormais un bouton **Supprimer** et sa suppression reste effective après redémarrage. La sauvegarde vérifie aussi sa copie locale et restaure l’état précédent en cas d’échec. Supprimer un serveur de la liste ne supprime pas les tickets, les ventes ni les comptes du routeur.

Tests : défauts reproduits avant correction, 13 scénarios de connexion, suite complète `npm run check`, preflight CLIENT et validation GitHub réussis. Essais dans le paquet Linux et dans Android Waydroid sur profils isolés : édition, relecture, redémarrage, suppression et redémarrage vide. Android **.39** installé sans désinstallation ; profils enregistrés, UID et données locales contrôlés. La connexion réelle à SMILE WIFI sur son PC Windows reste à vérifier ; ce poste n’était pas accessible pendant cette validation.

Les correctifs du portail, de Mobile Money, des durées en entier, du zoom et du trafic WAN Android sont conservés. Android peut lire les compteurs réels quand le PC partagé est indisponible, puis reprend les mesures communes ; les relevés mobiles ne sont pas ajoutés à l’historique du PC.

Android : **3.12.62.39**, certificat SHA-256 **000d5cadff59ad8f5228abcf663c1fc20533bb78fb645ac062394e9b30c1a2cc**. Certains APK plus anciens utilisent un autre certificat et demandent une migration avec sauvegarde ; ne pas les désinstaller automatiquement.

La version de base PC reste **3.12.62** : utilisez les fichiers **CONNEXION-IP-20261116** ci-dessus. Les anciennes releases restent disponibles dans l’historique.

macOS Intel et Apple Silicon : ZIP non signés et non notarisés, sans essai sur Mac réel. Windows sans Authenticode ; Linux sans signature GPG. Les tests réseau ne certifient pas tous les modèles des cinq constructeurs ; téléphone physique, paiements réels et parcours Hotspot jusqu’à expiration restent à valider. Les limites précédemment signalées pour WireGuard/BTH et le VPN Waydroid ne sont pas levées par cette mise à jour.

Vérification : [SHA256SUMS-CLIENT.txt](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexion-ip.20261116/SHA256SUMS-CLIENT.txt). Sauvegardez la base LIHETI avant mise à jour.
