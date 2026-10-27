# BLBrowser

**[👉 Pour installer l'application, cliquez ici](https://github.com/amandiofr/BLBrowser-releases/releases/latest/download/BLBrowser.apk)** (téléchargement direct de la dernière version), puis ouvrez le fichier téléchargé sur votre téléphone ou votre TV (détails dans [Installation](#installation)).

Navigateur Android plein écran minimaliste : pas de barre d'adresse, pas d'onglets, pas de barre d'outils. Juste la page, en plein écran.

Glissez depuis le bord gauche de l'écran pour ouvrir le menu : retour, recharger, accueil, recherche Google, saisie d'URL, mode sombre, luminosité, masquage d'éléments de la page. Sur Android TV / Google TV, la touche **Retour** de la télécommande ouvre le menu. Les publicités, traceurs et bannières de cookies sont bloqués automatiquement.

Ce dépôt sert uniquement à distribuer les APK de BLBrowser.

## Installation

1. Sur le téléphone, téléchargez [BLBrowser.apk](https://github.com/amandiofr/BLBrowser-releases/releases/latest/download/BLBrowser.apk) (toujours la dernière version).
2. Ouvrez l'APK téléchargé (notification de fin de téléchargement, ou application *Fichiers* → *Téléchargements*).
3. Si Android bloque l'installation, autorisez l'application qui ouvre l'APK (navigateur ou *Fichiers*) à installer des applications inconnues : *Paramètres* → *Applications* → *Accès spécial* → *Installer des applications inconnues*.
4. Si Google Play Protect affiche un avertissement (« application inconnue »), choisissez *Plus d'infos* → *Installer quand même*.

Compatibilité : Android 7.0 et supérieur, téléphones, tablettes et Android TV / Google TV.

## Mises à jour

Au démarrage, BLBrowser vérifie (au plus toutes les 12 heures) si une nouvelle version est publiée ici et propose de la télécharger. Il suffit ensuite d'ouvrir l'APK : la mise à jour s'installe par-dessus la version existante et conserve vos réglages (page d'accueil, mode sombre, éléments masqués).

Vous pouvez aussi télécharger manuellement la dernière version depuis [Releases](https://github.com/amandiofr/BLBrowser-releases/releases/latest).

## Vous aviez la version Google Play ?

BLBrowser n'est plus publié sur Google Play. Essayez d'abord d'installer l'APK par-dessus la version existante : vos réglages seront conservés. Si Android refuse (« L'application n'a pas été installée car le package est en conflit avec un package existant »), désinstallez la version Google Play puis installez l'APK ; vos réglages seront alors à refaire.

## Vérifier l'authenticité d'un APK

Ne téléchargez BLBrowser que depuis ce dépôt. Tous les APK officiels sont signés avec le certificat suivant :

```
SHA-256 : 47:21:45:BB:F7:37:B4:16:F0:AC:1E:5C:FE:CA:89:69:08:0E:FF:C8:A9:F1:AF:AD:DA:81:F5:F2:D5:4D:97:BC
```

Pour le vérifier depuis un ordinateur (outil `apksigner` du SDK Android) :

```
apksigner verify --print-certs BLBrowser-<version>.apk
```
