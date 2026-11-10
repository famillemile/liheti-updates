# LIHETI MANAGER CLIENT

> **VIP fonctionnel dans le correctif LIHETI GV1.** La création et la relecture ont été vérifiées sur MikroTik RB5009. Durée par défaut : 1 heure, modifiable ; débit Standard : 2,5 / 8 Mb/s par appareil, modifiable. Les nouveaux installateurs CLIENT corrigés sont maintenant disponibles sur la release VIP 2,5/8.

Gestion des tickets Internet, Hotspot et cybercafé, avec un moteur métier commun et des adaptateurs selon les capacités réelles des équipements.

- [Page de téléchargement FR / MG / EN](https://famillemile.github.io/liheti-updates/)
- [Nouvelle préversion V100 CLIENT — VIP corrigé 2,5/8, Android signé](https://github.com/famillemile/liheti-updates/releases/tag/v3.12.62-v100-vip25.20261110)

## Cinq constructeurs intégrés

| Constructeur | Mode de connexion présent |
|---|---|
| MikroTik | RB5009 et hAP ac² compatibles sous RouterOS 7 avec API REST activée ; tickets Hotspot et VIP multi-appareils |
| Cudy | Modèles OpenWrt/openNDS compatibles ; ou point d’accès derrière passerelle LIHETI |
| TP-Link | Omada 5.9+ Open API, modèles OpenWrt compatibles, ou point d’accès derrière passerelle |
| Tenda | Modèles OpenWrt/openNDS compatibles ; ou point d’accès derrière passerelle |
| Ubiquiti | API d’intégration officielle UniFi Network ; ou airOS/UniFi en point d’accès derrière passerelle |

Les fonctionnalités dépendent du modèle, du firmware, du contrôleur et de la passerelle. Cinq intégrations ne signifient pas cinq certifications matérielles. Les quatre autres marques restent à qualifier pour le VIP par appareil et son quota partagé.

## Fonctions et correctifs de cette préversion

- Débit par défaut **2,5 / 8 Mb/s par appareil**, modifiable.
- Trois modes : durée uniquement avec données illimitées, quota uniquement, ou durée + quota.
- Mode choisi enregistré ; quota activé partagé entre les appareils.
- Une création incertaine est relue avant toute reprise ; aucun second envoi aveugle.
- Réglages commerciaux partagés : débits, profils, tarifs et ligne VIP via le transport universel existant.
- Bluetooth Android : autorisations SCAN + CONNECT demandées avec consentement, sans attribution automatique.

Quatre installateurs CLIENT : Windows EXE, Linux DEB et AppImage, Android APK. Empreintes dans `SHA256SUMS.txt` sur la release. 

**Authenticité** : APK Android release signé avec le certificat historique CLIENT (`SHA-256 : 4e8466d8890a8bb4f3daf906fc0978ccb59d7a9bc8478b76f2998e643413eb22`). Windows ne possède pas de signature Authenticode et les paquets Linux de cette release ne sont pas signés GPG. Vérifiez les empreintes dans le manifeste `SHA256SUMS.txt`.

**Préversion de recette** : EXE sans Authenticode et PDF Android encore trop haut. Le paquet macOS universel est compilé pour QA privée, en attente de Developer ID et de notarisation. Les tests de convergence sur quatre contextes et de stockage natif Linux ont réussi ; la recette simultanée de quatre appareils physiques reste à compléter.

**Migration Android** : un APK release ne remplace pas directement une installation signée DEBUG. Sauvegarder les données et prévoir une migration contrôlée ; aucune désinstallation de téléphone sans sauvegarde.

[Manifeste SHA-256 des quatre nouveaux installateurs](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-v100-vip25.20261110/SHA256SUMS.txt)
