# DigitalWerk KI – iPhone-Version v0.4

Diese Version baut auf dem hochgeladenen v0.2-Prototyp auf und ergänzt die mobile Bedienung sowie PWA-Metadaten.

## iPhone einrichten
1. Die Dateien müssen über eine HTTPS-Adresse bereitgestellt werden (z. B. eine eigene Webadresse oder ein geeigneter statischer HTTPS-Host). Das Öffnen der ZIP-Datei direkt auf dem iPhone reicht nicht.
2. Öffne die HTTPS-Adresse in Safari.
3. Tippe auf „Teilen“ → „Zum Home-Bildschirm“.
4. Aktiviere „Als Web-App öffnen“, falls Safari die Option anbietet, und tippe auf „Hinzufügen“.
5. Starte DigitalWerk KI über das neue Symbol.

## Enthaltene Anpassungen
- Mobile Navigation mit horizontalem Wischen
- Größere Touch-Flächen und iPhone-gerechte Eingabefelder
- Safe-Area-Abstände für iPhone-Displays
- Angepasste Dialoge und Tabellen auf schmalen Displays
- PWA-Metadaten und App-Symbol
- Offline-App-Shell über den Service Worker

## Wichtige Grenzen
- Dies ist weiterhin ein Prototyp. Daten bleiben im Browser-/Web-App-Speicher dieses Geräts.
- Nicht gleichzeitig auf mehreren Geräten verwenden; es gibt noch keine Synchronisierung und keine transaktionssichere Mehrbenutzer-Datenbank.
- Offline-Funktion bedeutet nicht, dass jeder externe Dienst oder jede Browserfunktion offline verfügbar ist.
- Vor kommerziellem Einsatz sind umfangreiche Tests, Sicherheitsprüfung sowie steuerliche und rechtliche Prüfung nötig. Angebote/Rechnungen sind nicht als rechtssicher freigegeben.
- Der Service Worker funktioniert nur über HTTPS oder localhost. Für die Installation auf dem iPhone ist eine HTTPS-Bereitstellung erforderlich.
