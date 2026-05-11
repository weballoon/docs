# Installation und unterstützte Plattformen

Offizielle Desktop-Builds zielen auf **macOS**, **Windows** und **Linux**, für **64-Bit Intel (x64)** und **Apple Silicon / ARM64**, soweit zutreffend.

## macOS

Installer werden als **DMG** und **ZIP** bereitgestellt (beide Architekturen in Release-Builds). Nach dem Öffnen des DMG ziehen Sie **weballoon** in Programme (oder Ihren üblichen Ablauf).

**Deep-Link:** Die App registriert das Schema `weballoon://`, damit E-Mail-**Magic Links** beim Klick zur App zurückkehren.

## Windows

Das Release-Format ist **NSIS** (Installer) für x64 und arm64.

Dasselbe Schema **`weballoon://`** gilt für den Abschluss des Magic Links.

## Linux

Release-Builds nutzen **AppImage** (x64 und arm64). Automatische In-App-Updates unter Linux funktionieren ggf. nur bei Installation aus einem unterstützten Release-Paket (die App erklärt, wenn Updates in Ihrer Umgebung nicht verfügbar sind).

## Updates

Unter **Einstellungen**, im Kontobereich, erlaubt die Karte **App-Updates**, nach **Updates zu suchen** und bei bereitem Download **neu zu starten, um zu aktualisieren**. Wurde ein Update im Hintergrund geladen, kann weballoon Sie zu einem passenden Zeitpunkt zum Neustart auffordern.

Manche Umgebungen (z. B. lokale Entwicklungsbuilds) bieten keine automatischen Updates; die Karte zeigt dann „nicht verfügbar“ und den Grund.

## Systemanforderungen

weballoon ist eine Desktop-Web-Laufzeit. Für flüssigen Betrieb reicht ein normaler moderner Rechner mit einigen GB freiem RAM; jede geöffnete oder Hintergrund-App nutzt zusätzlich Speicher (siehe [Ruhezustand und Speicher](hibernation-and-memory.md)).
