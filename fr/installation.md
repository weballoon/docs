# Installation et plateformes prises en charge

Les builds bureau officiels ciblent **macOS**, **Windows** et **Linux**, en **Intel 64 bits (x64)** et **Apple Silicon / ARM64** le cas échéant.

## macOS

Les installateurs sont des **DMG** et **ZIP** (les deux architectures dans les builds de release). Après ouverture du DMG, faites glisser **weballoon** dans Applications (ou votre habitude).

**Lien profond :** l’app enregistre le schéma `weballoon://` pour que les **liens magiques** par e-mail rouvrent l’app au clic.

## Windows

Le format de release est **NSIS** (installateur) pour x64 et arm64.

Le même schéma **`weballoon://`** s’applique pour finaliser le lien magique.

## Linux

Les releases utilisent **AppImage** (x64 et arm64). Les mises à jour automatiques in-app sous Linux peuvent ne fonctionner que si vous avez installé depuis un paquet de release pris en charge (l’app indique si les mises à jour sont indisponibles dans votre environnement).

## Mises à jour

Dans **Réglages**, près de la zone compte, la carte **Mises à jour de l’app** permet de **vérifier les mises à jour** et, lorsqu’un téléchargement est prêt, de **redémarrer pour mettre à jour**. Si une mise à jour est téléchargée en arrière-plan, weballoon peut vous proposer de redémarrer quand c’est pratique.

Certains environnements (par exemple builds de développement local) n’offrent pas de mises à jour automatiques ; la carte indique qu’elles sont indisponibles et pourquoi.

## Configuration requise

weballoon est un runtime web bureau. Pour un usage fluide, un ordinateur moderne classique avec quelques Go de RAM libres suffit ; chaque app ouverte ou en arrière-plan consomme de la mémoire supplémentaire (voir [Hibernation et mémoire](hibernation-and-memory.md)).
