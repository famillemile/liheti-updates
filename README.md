# LIHETI MANAGER CLIENT — correctifs du 15 novembre 2026

Gestion des tickets Internet, Hotspot et cybercafé, avec un moteur métier commun et des adaptateurs selon les capacités des équipements.

- [Télécharger la version CLIENT corrigée — FR / MG / EN](https://famillemile.github.io/liheti-updates/)
- [Installateurs et notes de la livraison](https://github.com/famillemile/liheti-updates/releases/tag/v3.12.62-client-corrige.20261115.2)
- [Empreintes SHA-256](https://github.com/famillemile/liheti-updates/releases/download/v3.12.62-client-corrige.20261115.2/SHA256SUMS-CLIENT.txt)

## Fichiers actuels

| Plateforme | Version proposée |
|---|---|
| Android | CLIENT 3.12.62.36, signé avec le certificat CLIENT historique |
| Windows x64 | Installateur CLIENT 3.12.62 reconstruit le 15 novembre, sans Authenticode |
| Linux x64 | AppImage et paquet Ubuntu/Debian reconstruits le 15 novembre |
| macOS | ZIP Intel et Apple Silicon reconstruits le 15 novembre, non signés / non notarisés |

Cette livraison remplace les anciens liens de téléchargement CLIENT de la page publique. Les anciennes versions restent dans l’historique des releases.

## Correctifs et validation

Synchronisation du journal commercial et des mesures WAN entre appareils appairés ; correctifs des offres Hotspot, de la validation VIP, du nettoyage, de la réserve locale et du module VPN inclus dans les sources actuelles.

Back To Home testé à chaud sur Ubuntu et émulateur Android SDK avec un MikroTik RB5009 : connexion, reconnexion Android, accès de gestion et révocation vérifiés. QR fabriqué localement et expiration relative corrigés. Les accès d’essai ont été retirés et les données conservées.

Le tunnel VPN propre à Waydroid a échoué durant l’essai. Le même profil fonctionne sous Ubuntu ; l’essai Android SDK a réussi séparément. Aucun téléphone physique testé. L’import du profil dans WireGuard et l’autorisation VPN restent nécessaires ; partage natif Android et WireGuard direct public restent à valider. BTH était déjà actif avant le test. Windows/macOS : paquets contrôlés à la compilation, sans validation sur appareil réel. Cette livraison reste une préversion.

## Cinq constructeurs

MikroTik, Cudy, TP-Link, Tenda et Ubiquiti restent intégrés selon le modèle, le firmware, le contrôleur et la passerelle. Les essais VPN de cette intervention portent sur MikroTik ; la présence d’un pilote ne certifie pas tous ses modèles.

## Installation

APK Android release signé avec le certificat historique CLIENT : `4e8466d8890a8bb4f3daf906fc0978ccb59d7a9bc8478b76f2998e643413eb22`. Mise à jour sans désinstallation depuis un APK release compatible. Une installation DEBUG ou signée autrement nécessite une migration adaptée avec sauvegarde. Windows sans Authenticode ; Linux sans signature GPG pour cette livraison ; macOS non signé et non notarisé.

Vérifiez les empreintes du manifeste avant installation et sauvegardez vos données avant mise à jour. Les fichiers PERSO et les clés privées ne sont pas distribués par ce dépôt public.

## Lots STANDARD — correctif supplémentaire

Lots normaux corrigés : Ticket STANDARD, migration des anciens tickets code seul, attente du journal partagé et annulation pendant la préparation. Création vérifiée sur PC ; interface Android Waydroid vérifiée à 390 px. Création Android à chaud suspendue pendant une interruption ZeroTier. Les profils VIP et les ventes existantes sont conservés. Voir les notes de la nouvelle livraison.
