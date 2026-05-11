# Configuration du proxy

Ouvrez **Réglages → Proxy**.

## Routage par application

Chaque app peut passer par son **propre** proxy ou **aucun**. Utile pour :

- Les proxys HTTP d’entreprise uniquement sur les apps pro.
- L’accès SOCKS pour des outils précis.
- Les tests régionaux combinés à des sessions isolées.

## Champs (proxy activé)

- **Protocole** — HTTP, HTTPS, SOCKS4 ou SOCKS5.
- **Hôte** et **Port**.
- **Nom d’utilisateur** (facultatif).
- **Mot de passe** (facultatif). L’interface explique qu’un mot de passe enregistré peut rester vide pour conserver l’ancien, et qu’il existe une action pour **effacer le mot de passe enregistré**.
- **Règles d’exclusion** — Liste de style virgules (exemple dans l’app : `localhost, 127.0.0.1, *.internal`).

## Enregistrement

**Enregistrer et recharger** enregistre les réglages et **recharge cette application** pour que les nouvelles connexions empruntent la route. L’app avertit que les changements de proxy **ferment les connexions existantes** pour l’app concernée.

## Note de sécurité

La zone **Compte** indique que les **mots de passe du proxy** sont chiffrés sur cet appareil et **ne sont pas** synchronisés vers le cloud.

## Si la liste est vide

Ajoutez au moins une application d’abord ; l’écran du proxy l’explique.
