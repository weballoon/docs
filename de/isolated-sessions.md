# Isolierte Sitzungen

Jede weballoon-App läuft in einer **eigenen browserähnlichen Sitzung**. Sitzungen **teilen nicht**:

- Cookies  
- Local Storage und ähnliche Website-Daten  
- Anmeldezustand (außer Sie melden sich in jeder App separat an)

Zwei Apps für denselben Dienst (oder zwei Gmail-Installationen) verhalten sich wie **zwei getrennte Profile**, solange es separate App-Einträge sind.

## Warum das wichtig ist

- **Arbeit / Privat:** Derselbe Dienst, verschiedene Konten, ohne ständiges Hin- und Herwechseln in einer Tab-Leiste.
- **Sicherheit:** Eine riskante Site in ihrer eigenen App liest keine Cookies Ihrer Bank-App.
- **Planbarkeit:** Daten einer App löschen (unter **Einstellungen → Datenschutz und Daten**) betrifft **nur** diese App.

## „Standardansicht“ schwächt die Isolation nicht

Standard vs. benannter Bereich ist nur **Organisation**. Isolation ist **pro App**, nicht pro Bereichsname.

## Verwandte Einstellungen

- **Datenschutz und Daten** — Eine oder alle Apps löschen; optional automatisches Löschen beim Beenden; Do Not Track; Diagnose optional; lokalen Datenordner öffnen.
- **Berechtigungen** — Kamera, Mikrofon, Bildschirmfreigabe und Standort sind **standardmäßig blockiert**, bis Sie sie pro App erlauben.

Siehe [Datenschutz und lokale Daten](privacy-and-local-data.md) und [Berechtigungen](permissions.md).
