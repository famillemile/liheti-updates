# LIHETI MANAGER CLIENT

Téléchargements du **17 novembre 2026 — connexions et portail** : [page officielle](https://famillemile.github.io/liheti-updates/) · [release](https://github.com/famillemile/liheti-updates/releases/tag/v3.12.62-client-connexions-vip.20261117).

| Plateforme | Fichier |
| --- | --- |
| Android CLIENT 3.12.62.40 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexions-vip.20261117/LIHETI-GV1-CLIENT-3.12.62.40-CONNEXIONS-VIP-20261117.apk) |
| Windows CLIENT — connexions et portail — 17/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexions-vip.20261117/LIHETI-GV1-CLIENT-Setup-3.12.62-CONNEXIONS-VIP-20261117.exe) |
| Linux CLIENT — connexions et portail — 17/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexions-vip.20261117/LIHETI-GV1-CLIENT-3.12.62-CONNEXIONS-VIP-20261117-x86_64.AppImage) |
| Ubuntu / Debian CLIENT — connexions et portail — 17/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexions-vip.20261117/LIHETI-GV1-CLIENT-3.12.62-CONNEXIONS-VIP-20261117-amd64.deb) |
| macOS Intel — connexions et portail — 17/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexions-vip.20261117/LIHETI-GV1-CLIENT-3.12.62-CONNEXIONS-VIP-20261117-x64.zip) |
| macOS Apple Silicon — connexions et portail — 17/11/2026 | [Télécharger](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexions-vip.20261117/LIHETI-GV1-CLIENT-3.12.62-CONNEXIONS-VIP-20261117-arm64.zip) |

Les adresses CLIENT sont libres : chaque utilisateur peut ajouter, modifier, choisir ou supprimer ses connexions. La synchronisation ne réapplique plus une ancienne copie des profils. Un échec de connexion garde le serveur choisi ; le dernier serveur supprimé ne revient pas au redémarrage.

Validation : dix nouvelles régressions de synchronisation, les scénarios du cycle de connexion, la suite complète `npm run check` et la CI GitHub réussis. Dans le paquet Linux, deux profils temporaires ont été ajoutés au CLIENT déjà configuré puis retirés après vérification de leur persistance ; les profils d’origine ont été conservés. Une lecture API native du RB5009 a réussi. Android Waydroid a passé les essais de trois profils et la mise à jour **.39 → .40** sans désinstallation, avec contrôle des profils, de l’UID et des données locales.

Le portail actualise le mot de passe caché lors de l’envoi du code, y compris après remplissage automatique ou nouvelle tentative, en PAP et CHAP. **Le refus VIP chez le client hAP ac² reste à valider par une connexion réelle à son Hotspot.** Création et vente ne suffisent pas à certifier cette étape.

Les corrections précédentes du trafic WAN Android, des tarifs, de Mobile Money, des durées et du zoom sont conservées. Les données commerciales et les connexions PERSO ne sont pas remplacées par cette correction.

Android : **3.12.62.40**, certificat SHA-256 **000d5cadff59ad8f5228abcf663c1fc20533bb78fb645ac062394e9b30c1a2cc**. Les anciennes installations signées avec un autre certificat nécessitent une migration sauvegardée.

La version de base PC reste **3.12.62** : utilisez les fichiers **CONNEXIONS-VIP-20261117**. Windows et macOS ont été compilés et contrôlés, sans nouvel essai sur appareil physique. macOS Intel et Apple Silicon : ZIP non signés et non notarisés Apple. Windows sans Authenticode ; Linux sans signature GPG.

Vérification : [SHA256SUMS-CLIENT.txt](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-connexions-vip.20261117/SHA256SUMS-CLIENT.txt). Les anciennes releases restent dans l’historique. Sauvegardez la base avant mise à jour.
