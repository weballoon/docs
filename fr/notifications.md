# Notifications

weballoon gère deux idées liées : les **notifications au niveau du système** des sites qui utilisent l’API de notification du navigateur, et une **liste de notifications dans l’app** pour rattraper le retard sans chercher des toasts.

## Centre de notifications in-app

- Cliquez sur la **cloche** du dock, ou **Maj+N** (selon le focus ; voir [Raccourcis clavier](keyboard-shortcuts.md)).
- Vous pouvez **tout marquer comme lu**, ouvrir un élément pour aller à l’app ou supprimer des entrées.
- Lorsque vous **consultez déjà** une app, les nouvelles notifications de cette même app ne sont **pas dupliquées** dans la liste interne (l’app peut encore utiliser la notification du système si le site le permet).

Les notifications sont conservées dans une courte liste (jusqu’à 100 éléments récents) pour garder le panneau utile.

## « Exécuter en arrière-plan » (par app)

Dans **Réglages → Notifications**, chaque app a une option intitulée **Run in background** dans l’interface anglaise. Si elle est activée :

- La session de cette app peut rester active pour que des éléments comme les **websockets** continuent lorsque vous regardez une autre app ou un autre espace.
- weballoon rappelle que **chaque** app en arrière-plan utilise environ **50 à 150 Mo** de mémoire (approximatif ; l’usage réel varie selon le site).

Si vous n’avez pas encore d’apps, le panneau indique d’abord d’ajouter des apps, puis de choisir lesquelles doivent rester actives.

## Usage pratique

- Activez **Exécuter en arrière-plan** pour le chat ou le mail où vous voulez des alertes pendant que vous travaillez ailleurs dans weballoon.
- Laissez-la désactivée pour les sites lourds ou peu utilisés pour économiser la RAM.

Voir aussi [Hibernation et mémoire](hibernation-and-memory.md).
