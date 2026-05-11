# Proxy-Konfiguration

**Einstellungen → Proxy** öffnen.

## Routing pro Anwendung

Jede App kann über einen **eigenen** Proxy oder **keinen** laufen. Nützlich für:

- Firmen-HTTP-Proxys nur für Arbeits-Apps.
- SOCKS-Zugang für bestimmte Tools.
- Regionale Tests zusammen mit isolierten Sitzungen.

## Felder (Proxy aktiv)

- **Protokoll** — HTTP, HTTPS, SOCKS4 oder SOCKS5.
- **Host** und **Port**.
- **Benutzername** (optional).
- **Passwort** (optional). Die Oberfläche erklärt: gespeichertes Passwort leer lassen behält das alte; Aktion zum **gespeicherten Passwort löschen**.
- **Umgehungsregeln** — kommagetrennte Liste (Beispiel in der App: `localhost, 127.0.0.1, *.internal`).

## Speichern

**Speichern und neu laden** speichert und **lädt diese Anwendung neu**, damit neue Verbindungen die Route nutzen. Die App warnt: Proxy-Änderungen **schließen bestehende Verbindungen** der betroffenen App.

## Sicherheitshinweis

Im **Konto**-Bereich: **Proxy-Passwörter** werden auf diesem Gerät verschlüsselt und **nicht** in die Cloud synchronisiert.

## Leere Liste

Zuerst mindestens eine Anwendung hinzufügen; der Proxy-Bildschirm erklärt das.
