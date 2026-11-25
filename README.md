# DigitalWerk KI – Handwerker Cockpit v0.2

## Enthalten
- Dashboard, Kalkulation, Kunden, Projekte, Angebote
- Lagerbestand mit Artikelnummer, Einheit, Startbestand, Mindestbestand, Einkaufspreis, Lieferant und Lieferzeit
- Materialbedarfspositionen je Kalkulation/Angebot
- Einmalige Angebotsannahme mit Materialreservierung
- Bestellvorschläge bei Fehlmengen
- Wareneingang und Lagerbewegungsprotokoll
- Materialausgabe erst nach Bestandsprüfung; Reservierungen werden anschließend freigegeben
- JSON-Backup/Wiederherstellung
- PWA-Manifest und Service Worker

## Wichtiger Ablauf
1. Im Lager Material mit Bestand und Mindestbestand anlegen.
2. In einer Kalkulation Materialbedarfspositionen hinzufügen.
3. Angebot speichern.
4. In Angebote „Annehmen & reservieren“ wählen.
5. Fehlmengen erscheinen als Bestellvorschläge.
6. Nach Wareneingang buchen; anschließend Material entnehmen.

## Grenzen des Prototyps
- Lokale Browserdaten; keine geräteübergreifende Synchronisierung.
- Die lokale Speicherung ist noch keine transaktionssichere Mehrbenutzer-Lagerverwaltung. Nicht parallel auf mehreren Geräten verwenden.
- Bestellvorschläge werden nicht automatisch an Lieferanten gesendet.
- Vor kommerziellem Einsatz sind weitere Tests, IndexedDB-/Transaktionsmigration, Sicherheits- und Rechtsprüfung erforderlich.
- Angebots- und Rechnungsdokumente sind noch nicht rechtssicher freigegeben.
