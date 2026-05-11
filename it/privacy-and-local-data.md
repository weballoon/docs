# Privacy e dati locali

Apri **Impostazioni → Privacy e dati**.

## Cosa resta locale

L’app sottolinea che i tuoi **dati restano sul tuo computer**. La schermata mostra:

- **Archiviazione** approssimativa usata nella cartella dati utente.
- Conteggi di **app** e **spazi di lavoro**.
- Percorso al file principale del database locale (mostrato come `weballoon.json` nella cartella dati).
- **Apri cartella** — apre quella directory nel gestore file di sistema.

## Cancellare i dati

- **Cancella dati** (per app) — Rimuove cookie, cache e dati del sito archiviati per quella sessione isolata. L’app può ricaricarsi al prossimo avvio.
- **Cancella tutti i dati** — Rimuove cookie, cache e archiviazione **per tutte le app**. È distruttivo; weballoon chiede conferma.

## Pulizia automatica (in uscita)

Due interruttori persistono tra i riavvii:

1. **Cancella automaticamente all’uscita** — Alla chiusura di weballoon vengono cancellati i dati di navigazione delle app (cookie, cache e tipi di archiviazione che l’app cancella in uscita).
2. **Cancella cache automaticamente** — Nonostante testi più vecchi parlino di «periodicamente», l’implementazione cancella la **cache alla chiusura** di weballoon (non con un timer durante il giorno). Se entrambe le opzioni automatiche sono attive, prevale il percorso più forte di cancellazione completa in uscita.

## Do Not Track

**Invia intestazione Do-Not-Track** chiede ai siti di rispettare il DNT. Non tutti lo fanno; è una richiesta, non una garanzia.

## Rapporti su arresti anomali ed errori

**Condividi rapporti su arresti anomali ed errori** è **disattivato per impostazione predefinita**. Se lo attivi, l’app descrive l’invio di **diagnostica tecnica anonimizzata** per migliorare la stabilità, **non** il contenuto di navigazione, le credenziali o la cronologia.

## Isolamento delle app (promemoria)

Ogni app ha **archiviazione isolata**. La cancellazione o la cancellazione automatica colpisce **quella partizione**, non le altre app.

Vedi [Sessioni isolate](isolated-sessions.md).
