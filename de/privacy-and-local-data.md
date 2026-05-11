# Datenschutz und lokale Daten

**Einstellungen → Datenschutz und Daten** öffnen.

## Was lokal bleibt

Die App betont, dass Ihre **Daten auf Ihrem Computer** bleiben. Die Einstellungsseite zeigt:

- Ungefähren **Speicher** unter dem Benutzerdatenordner.
- Zähler für **Apps** und **Arbeitsbereiche**.
- Pfad zur Hauptdatenbankdatei (als `weballoon.json` unter Ihrem Benutzerdatenordner).
- **Ordner öffnen** — öffnet diesen Datenordner im Dateimanager.

## Daten löschen

- **Daten löschen** (pro App) — Entfernt Cookies, Cache und Website-Speicher dieser isolierten Sitzung. Die App kann beim nächsten Öffnen neu laden.
- **Alle Daten löschen** — Entfernt Cookies, Cache und Speicher **für alle Apps**. Zerstörerisch; weballoon fragt nach Bestätigung.

## Automatische Bereinigung (beim Beenden)

Zwei Schalter bleiben über Neustarts erhalten:

1. **Beim Beenden automatisch löschen** — Beim Beenden von weballoon werden Browser-Daten der Apps gelöscht (Cookies, Cache und die beim Beenden gelöschten Speichertypen).
2. **Cache automatisch löschen** — Trotz älterem Wortlaut „regelmäßig“ wird der **Cache beim Beenden** von weballoon geleert (kein Timer tagsüber). Sind beide Auto-Optionen an, gilt der stärkere Weg „Browserdaten beim Beenden löschen“.

Nutzen Sie das, wenn Sie nach jeder Sitzung „frisch“ starten wollen.

## Do Not Track

**Do-Not-Track-Header senden** bittet Sites um DNT-Respekt. Nicht alle Sites befolgen das; es ist eine Bitte, keine Garantie.

## Absturz- und Fehlerberichte

**Absturz- und Fehlerberichte teilen** ist **standardmäßig aus**. Wenn aktiv, beschreibt die App den Versand **bereinigter technischer Diagnosedaten** zur Stabilität, **nicht** Ihres Browser-Inhalts, Ihrer Zugangsdaten oder Verlaufs.

## App-Isolation (Erinnerung)

Jede App hat **isolierten Speicher**. Löschen oder Auto-Löschen betrifft **diese Partition**, nicht Ihre anderen Apps.

Siehe [Isolierte Sitzungen](isolated-sessions.md).
