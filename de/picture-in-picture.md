# Bild-in-Bild (Video)

weballoon enthält ein **schwebendes Videofenster** (englisch ggf. **PiP Video**), um einen Stream zu sehen, während Sie andere Teile der App nutzen.

## Öffnen

**Umschalt+S** drücken (oder dasselbe aus einer eingebetteten App).

## Nutzung

1. Ein kleines schwebendes Fenster öffnet sich.
2. **Video-Seiten-URL** einfügen oder eingeben und **Wiedergeben** (oder Formular absenden).
3. Bei gängigen Hosts wandelt weballoon Links in einen **Embed**-Player um, wenn möglich:
   - **YouTube** (`youtube.com/watch?v=…` oder `youtu.be/…`)
   - **Vimeo**
   - **Dailymotion**
4. Andere URLs laden **direkt im iframe**; Wiedergabe hängt von den Embed-Regeln der Site ab (manche blockieren iframes).

## Steuerung

- **Schließen** — schließt das Fenster und leert die URL.
- **URL ändern** (bei aktivem Video) — zurück zur URL-Eingabe.
- **Position zurücksetzen** — nach Verschieben Layout zurücksetzen (Symbol mit Pfeilen in der Leiste).
- **Ziehen** am leeren Rahmen (nicht über Felder, Buttons oder iframe).

## Hinweise

- **Nicht** die native Browser-PiP-API für beliebige Tabs; weballoons eigenes **PiP-Schwebefenster** mit iframe-Wiedergabe.
- Autoplay hängt von Site und System-Audio ab.
