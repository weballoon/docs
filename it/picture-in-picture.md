# Picture-in-picture (video)

weballoon include un **pannello video flottante** (in inglese può essere etichettato **PiP Video**) per guardare uno stream mentre usi altre parti dell’app.

## Aprire il pannello

Premi **Maiusc+S** (o la stessa scorciatoia da dentro un’app incorporata).

## Utilizzo

1. Si apre una piccola finestra flottante.
2. Incolla o digita un **URL di pagina video** e premi **Riproduci** (o invia il modulo).
3. Per host comuni, weballoon converte i link in un lettore **incorporato** se possibile:
   - **YouTube** (`youtube.com/watch?v=…` o `youtu.be/…`)
   - **Vimeo**
   - **Dailymotion**
4. Altri URL si caricano **direttamente nell’iframe**; la riproduzione dipende dalle regole di embedding del sito.

## Controlli

- **Chiudi** — chiude il flottante e cancella l’URL.
- **Cambia URL** (con video attivo) — torna all’inserimento URL.
- **Ripristina posizione** — dopo aver spostato la finestra, un controllo può ripristinare il layout.
- Puoi **trascinare** il pannello dal chrome vuoto (non input, pulsanti o iframe).

## Note

- **Non** è l’API PiP nativa del browser per schede arbitrarie; è il **flottante PiP** dedicato di weballoon con riproduzione in iframe.
- L’autoplay può dipendere dal sito e dalle impostazioni audio di sistema.
