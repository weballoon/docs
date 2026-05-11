# Image dans l’image (vidéo)

weballoon inclut un **panneau vidéo flottant** (en anglais, libellé possible **PiP Video**) pour regarder un flux pendant que vous utilisez d’autres parties de l’app.

## Ouvrir le panneau

Appuyez sur **Maj+S** (ou le même raccourci depuis une app intégrée).

## Utilisation

1. Une petite fenêtre flottante s’ouvre.
2. Collez ou saisissez une **URL de page vidéo** et appuyez sur **Lire** (ou validez le formulaire).
3. Pour les hôtes courants, weballoon convertit les liens en lecteur **intégré** si possible :
   - **YouTube** (`youtube.com/watch?v=…` ou `youtu.be/…`)
   - **Vimeo**
   - **Dailymotion**
4. Les autres URL se chargent **directement dans l’iframe** ; la lecture dépend des règles d’intégration du site (certains bloquent les iframes).

## Contrôles

- **Fermer** — ferme le flottant et efface l’URL.
- **Changer d’URL** (vidéo active) — revient à la saisie d’URL.
- **Réinitialiser la position** — si vous avez déplacé la fenêtre, un contrôle peut rétablir la disposition (icône avec flèches type agrandissement dans la barre).
- Vous pouvez **faire glisser** le panneau par le chrome vide (pas les champs, boutons ni iframe).

## Notes

- Ce **n’est pas** l’API native image-dans-l’image du navigateur pour des onglets quelconques ; c’est le **flottant PiP** dédié de weballoon avec lecture en iframe.
- La lecture automatique peut dépendre du site et des réglages audio du système.
