# LIHETI MANAGER CLIENT

Gestion des tickets Internet, Hotspot et cybercafé, avec un moteur métier commun et des adaptateurs selon les capacités réelles des équipements.

- [Page de téléchargement FR / MG / EN](https://famillemile.github.io/liheti-updates/)
- [Préversion V100 CLIENT — correctifs VIP du 10 novembre 2026](https://github.com/famillemile/liheti-updates/releases/tag/v3.12.62-v100-vip-fix.20261110)

## Cinq constructeurs intégrés

| Constructeur | Mode de connexion présent |
|---|---|
| MikroTik | RouterOS 7 REST pour le pilote VIP par appareil |
| Cudy | Modèles OpenWrt/openNDS compatibles ; ou point d’accès derrière passerelle LIHETI |
| TP-Link | Omada 5.9+ Open API, modèles OpenWrt compatibles, ou point d’accès derrière passerelle |
| Tenda | Modèles OpenWrt/openNDS compatibles ; ou point d’accès derrière passerelle |
| Ubiquiti | API d’intégration officielle UniFi Network ; ou airOS/UniFi en point d’accès derrière passerelle |

Les fonctionnalités dépendent du modèle, du firmware, du contrôleur et de la passerelle. Cinq intégrations ne signifient pas cinq certifications matérielles. Les quatre autres marques restent à qualifier pour le VIP par appareil et son quota partagé.

## Correctifs VIP de cette préversion

- Débit par défaut **2,8 / 8 Mb/s par appareil**, modifiable.
- Trois modes : durée uniquement avec données illimitées, quota uniquement, ou durée + quota.
- Mode choisi enregistré ; quota activé partagé entre les appareils.
- Une création incertaine est relue avant toute reprise ; aucun second envoi aveugle.

Quatre installateurs CLIENT : Windows EXE, Linux DEB et AppImage, Android APK. Empreintes dans `SHA256SUMS.txt` sur la release. Aucun installateur PERSO publié.

**Préversion de recette** : APK signé DEBUG, EXE sans Authenticode, PDF Android encore trop haut. Le correctif de délai doit être exercé sur le hAP ac² lent. Aucun binaire macOS V100 fourni à ce stade. La synchronisation immédiate de tous les nouveaux réglages sur Android, Windows, Linux et macOS est en cours de validation ; elle n’est pas certifiée par cette release.
