# Dépannage

Étapes posées et pratiques. Si rien n’aide, notez la **version de weballoon** (Réglages → Mises à jour de l’app) et l’**OS** en demandant de l’aide.

## Le lien magique ne lie pas l’appareil

- Vérifiez que vous avez cliqué sur le lien sur la **même machine** où weballoon est installé.
- macOS / Windows : assurez-vous que les liens **`weballoon://`** ouvrent weballoon (réglages du « gestionnaire par défaut »).
- Essayez **Renvoyer le lien** dans **Réglages → Compte** après le délai.
- Consultez les dossiers spam.

## « Limite de l’offre gratuite atteinte »

Vous avez **10 apps** ou essayez de créer plus de **2** espaces en Free. Supprimez une app ou un espace, ou passez à une offre supérieure sous **Offres** ([Offres et facturation](plans-and-billing.md)).

## Le site semble cassé ou vide

- **Actualiser** dans la barre de titre.
- **Réglages → Bloqueur de publicités** — essayez de désactiver le blocage **pour cette app seulement**.
- **Réglages → Proxy** — vérifiez hôte, port et exclusions ; enregistrez et laissez l’app recharger.

## Pas de notifications d’un site

- Activez **Exécuter en arrière-plan** pour cette app dans **Réglages → Notifications**.
- Le site doit vraiment utiliser les **notifications web** ; certains n’ont que des toasts dans la page.
- Si vous **êtes dans** cette app avec le focus, weballoon peut éviter de dupliquer les entrées dans la cloche interne (les notifications système peuvent encore apparaître selon le site).

## Le raccourci ne fonctionne pas

- Cliquez en dehors des champs du site (barre de titre ou chrome weballoon), puis réessayez ([Raccourcis clavier](keyboard-shortcuts.md)).
- Les sauts **Ctrl/Cmd+chiffre** vers un espace ne sont pris **que** dans une app web ouverte ; depuis **Mes apps** ou **Réglages**, utilisez le bouton d’espace ou **Maj+W**.

## CPU ou RAM élevés

- **Réglages → Gestionnaire des tâches** — triez par mémoire ou CPU.
- Réduisez les apps **Exécuter en arrière-plan**.
- Fermez les vues d’app inutilisées.

## Les mises à jour n’apparaissent jamais

La carte **Mises à jour de l’app** explique quand les vérifications automatiques sont **désactivées** (builds de développement, certaines configs Linux ou variables d’environnement). Installez un **release** officiel quand c’est possible.

## Fenêtre fermée mais weballoon « toujours là » (Windows / Linux)

Une **icône de barre d’état** peut tourner. **Clic droit → Quitter** pour quitter complètement, ou clic sur l’icône pour réafficher la fenêtre ([Vue d’ensemble des réglages](settings.md)).

## Mauvais thème après changement système

Le thème de weballoon est **manuel** (sombre / clair) dans Réglages, pas « suivre le système » dans le sélecteur actuel — choisissez le thème voulu dans **Apparence**.
