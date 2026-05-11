# Confidentialité et données locales

Ouvrez **Réglages → Confidentialité et données**.

## Ce qui reste local

L’app insiste sur le fait que vos **données restent sur votre ordinateur**. L’écran de réglages affiche :

- Le **stockage** approximatif utilisé dans la zone de données utilisateur.
- Le nombre d’**apps** et d’**espaces de travail**.
- Le chemin vers le fichier principal de base locale (affiché comme `weballoon.json` dans votre dossier de données utilisateur).
- **Ouvrir le dossier** — ouvre ce répertoire de données dans le gestionnaire de fichiers du système.

## Effacer les données

- **Effacer les données** (par app) — Supprime les cookies, le cache et les données du site stockées pour cette session isolée. L’app peut se recharger au prochain lancement.
- **Tout effacer** — Supprime cookies, cache et stockage **pour toutes les apps**. C’est destructif ; weballoon demande confirmation.

## Nettoyage automatique (à la sortie)

Deux interrupteurs persistent entre les redémarrages :

1. **Effacer automatiquement à la sortie** — À la fermeture de weballoon, les données de navigation des apps sont effacées (cookies, cache et types de stockage effacés à la sortie).
2. **Effacer le cache automatiquement** — Malgré d’anciennes mentions « périodiquement », l’implémentation efface le **cache à la fermeture de weballoon** (pas sur un minuteur dans la journée). Si les deux options automatiques sont actives, le chemin le plus fort « effacer les données de navigation à la sortie » s’applique.

Utilisez-les si vous voulez repartir à zéro après chaque session.

## Do Not Track

**Envoyer l’en-tête Do-Not-Track** demande aux sites de respecter le DNT. Tous ne le font pas ; c’est une demande, pas une garantie.

## Rapports de plantages et d’erreurs

**Partager les rapports de plantages et d’erreurs** est **désactivé par défaut**. Si vous l’activez, l’app décrit l’envoi de **diagnostics techniques nettoyés** pour améliorer la stabilité, **pas** votre contenu de navigation, identifiants ou historique.

## Isolation des apps (rappel)

Chaque app a un **stockage isolé**. Effacer ou l’effacement automatique touche **cette partition**, pas vos autres apps.

Voir [Sessions isolées](isolated-sessions.md).
