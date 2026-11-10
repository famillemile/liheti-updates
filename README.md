# LIHETI MANAGER CLIENT

> **VIP fonctionnel dans le correctif LIHETI GV1.** La création et la relecture ont été vérifiées sur MikroTik RB5009. Durée par défaut : 1 heure, modifiable ; débit Standard : 2,5 / 8 Mb/s par appareil, modifiable. Les liens de la préversion ci-dessous pointent encore vers les anciens installateurs jusqu'à leur remplacement par les nouvelles compilations.

Gestion des tickets Internet, Hotspot et cybercafé, avec un moteur métier commun et des adaptateurs selon les capacités réelles des équipements.

- [Page de téléchargement FR / MG / EN](https://famillemile.github.io/liheti-updates/)
- [Préversion V100 CLIENT — Android signé, Linux GPG et réglages partagés](https://github.com/famillemile/liheti-updates/releases/tag/v3.12.62-v100-sync4.20261110)

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

**Signatures** : APK Android release signé avec le certificat historique CLIENT, non DEBUG ; mise à jour versionCode 8 vers 22 vérifiée dans l’émulateur. Linux DEB et AppImage accompagnés de signatures GPG vérifiées. Empreinte publique : `E0996A03C0484D62559DDBD1A951F5974E07555A`. [Clé publique](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-v100-sync4.20261110/LIHETI-RELEASE-PUBLIC-KEY.asc) · [Manifeste signé](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-v100-sync4.20261110/SHA256SUMS.txt.asc).

**Préversion de recette** : EXE sans Authenticode et PDF Android encore trop haut. Le paquet macOS universel est compilé pour QA privée, en attente de Developer ID et de notarisation. Les tests de convergence sur quatre contextes et de stockage natif Linux ont réussi ; la recette simultanée de quatre appareils physiques reste à compléter.

**Migration Android** : un APK release ne remplace pas directement une installation signée DEBUG. Sauvegarder les données et prévoir une migration contrôlée ; aucune désinstallation de téléphone sans sauvegarde.

[Rapport de tests et checklist](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-v100-sync4.20261110/RAPPORT-SYNC4-SIGNATURES.md)
