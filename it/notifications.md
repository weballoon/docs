# Notifiche

weballoon gestisce due idee collegate: **notifiche a livello di sistema** dai siti che usano l’API di notifica del browser e un **elenco di notifiche in-app** per recuperare senza cercare i toast.

## Centro notifiche in-app

- Fai clic sulla **campanella** nel dock, o **Maiusc+N** (se il focus lo consente; vedi [Scorciatoie da tastiera](keyboard-shortcuts.md)).
- Puoi **segna tutto come letto**, aprire una voce per andare all’app o eliminare voci.
- Mentre **stai già guardando** un’app, le nuove notifiche da quella stessa app **non sono duplicate** nell’elenco interno (l’app può ancora usare la notifica di sistema se il sito lo supporta).

Si mantengono fino a **100** voci recenti.

## «Esegui in background» (per app)

In **Impostazioni → Notifiche**, ogni app ha un’opzione con etichetta inglese **Run in background**. Se attiva:

- La sessione di quell’app può restare attiva affinché elementi come i **websocket** continuino mentre guardi un’altra app o un altro spazio.
- weballoon ricorda che **ogni** app in background usa circa **50–150 MB** di memoria (approssimativo; varia per sito).

Senza app, il pannello chiede prima di aggiungere le app.

## Uso pratico

- Attiva **Esegui in background** per chat o posta se vuoi avvisi mentre usi altre parti di weballoon.
- Lasciala disattivata per siti pesanti o raramente usati per risparmiare RAM.

Vedi anche [Ibernazione e memoria](hibernation-and-memory.md).
