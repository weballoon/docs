# Sessions isolées

Chaque app weballoon s’exécute dans sa **propre session de type navigateur**. Les sessions ne **partagent pas** :

- Les cookies  
- Le stockage local et données similaires du site  
- L’état connecté (sauf si vous vous connectez séparément dans chaque app)

Ainsi, deux apps pour le même service (ou deux installations Gmail) se comportent comme **deux profils distincts**, tant qu’il s’agit d’entrées d’app séparées.

## Pourquoi c’est important

- **Travail / perso :** même service, comptes différents, sans basculer sans cesse dans une seule rangée d’onglets.
- **Sécurité :** un site risqué dans sa propre app ne lit pas les cookies de votre app bancaire.
- **Prévisibilité :** effacer les données d’une app (dans **Réglages → Confidentialité et données**) ne cible **que** cette app.

## La « vue par défaut » n’affaiblit pas l’isolation

Par défaut vs espace nommé n’est qu’**organisation**. L’isolation est **par app**, pas par nom d’espace.

## Réglages liés

- **Confidentialité et données** — Effacer une app ou toutes les apps ; effacement automatique optionnel à la sortie ; Do Not Track ; diagnostics optionnels ; ouvrir votre dossier de données local.
- **Autorisations** — Caméra, micro, partage d’écran et géolocalisation sont **bloqués par défaut** jusqu’à ce que vous les autorisiez par app.

Voir [Confidentialité et données locales](privacy-and-local-data.md) et [Autorisations](permissions.md).
