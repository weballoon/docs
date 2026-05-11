# Flux de travail et astuces

Des schémas réels adaptés au modèle **apps isolées** et **espaces de travail** de weballoon.

## Travail vs personnel

1. Créez les espaces **Travail** et **Personnel**.
2. Ajoutez chaque site comme **sa propre app** pour que les sessions ne se mélangent pas.
3. Utilisez **Maj+W** pour changer de contexte rapidement.

## Multi-comptes sur un même service

Ajoutez **deux apps** avec des noms différents (par ex. « Gmail — travail » et « Gmail — maison ») pointant vers le même hôte. Chacune garde ses cookies. Vous ne pouvez pas dupliquer la **même URL dans un espace** ; placez la seconde copie dans un autre espace ou utilisez des URL d’entrée distinctes si le service les propose.

## Recherche et concentration

- Mettez les réseaux sociaux distrayants dans un **espace séparé** de la documentation.
- Désactivez **Exécuter en arrière-plan** pour les sites lourds que vous ne consultez qu’occasionnellement ([Notifications](notifications.md)).

## Appels et réunions

Activez **Caméra** et **Microphone** uniquement pour l’app vidéo de confiance ([Autorisations](permissions.md)). Si le site échoue encore, vérifiez si le **bloqueur de publicités** casse la page et désactivez-le pour cette seule app ([Bloqueur de publicités](adblocker.md)).

## Usage proxy poussé (dont SEO ou vérifications régionales)

weballoon **n’intègre pas** de suite SEO. Il **prend en charge** des **proxys HTTP/HTTPS/SOCKS par app** ([Proxy](proxy.md)). Schéma pratique :

- Un espace pour les outils **nationaux** (sans proxy).
- Un autre espace ou des entrées d’app pour des contrôles **géo** passant par un proxy que vous avez déjà chez un fournisseur légitime.

Respectez toujours les conditions du fournisseur et la loi applicable.

## Ordinateur partagé

- Utilisez la **protection par PIN** sur les apps perso ([Protection par code PIN](pin-protection.md)).
- Envisagez **Effacer automatiquement à la sortie** dans Confidentialité ([Confidentialité et données locales](privacy-and-local-data.md)).

## Machines peu dotées en mémoire

- Limitez les apps **Exécuter en arrière-plan**.
- Gardez moins de grosses apps « ouvertes » à la fois ; utilisez la grille et acceptez des rechargements occasionnels ([Hibernation et mémoire](hibernation-and-memory.md)).
