# Configurazione proxy

Apri **Impostazioni → Proxy**.

## Routing per applicazione

Ogni app può passare attraverso il **proprio** proxy o **nessuno**. Utile per:

- Proxy HTTP aziendali solo per app di lavoro.
- Accesso SOCKS per strumenti specifici.
- Test regionali combinati con sessioni isolate.

## Campi (proxy attivo)

- **Protocollo** — HTTP, HTTPS, SOCKS4 o SOCKS5.
- **Host** e **Porta**.
- **Nome utente** (facoltativo).
- **Password** (facoltativo). L’interfaccia spiega che una password salvata può restare vuota per mantenere la precedente; c’è un’azione per **cancellare password salvata**.
- **Regole di esclusione** — elenco tipo virgole (esempio nell’app: `localhost, 127.0.0.1, *.internal`).

## Salvataggio

**Salva e ricarica** salva le impostazioni e **ricarica quell’applicazione** affinché le nuove connessioni usino il percorso. L’app avvisa che le modifiche al proxy **chiudono le connessioni esistenti** dell’app interessata.

## Nota sulla sicurezza

L’area **Account** indica che le **password del proxy** sono crittografate su questo dispositivo e **non** sincronizzate nel cloud.

## Se l’elenco è vuoto

Aggiungi almeno un’applicazione prima; la schermata del proxy lo spiega.
