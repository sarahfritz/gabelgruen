# Gabelgrün – mobile Web-App

Diese Version ist für GitHub Pages und die Nutzung im mobilen Safari-Browser vorbereitet.

## Veröffentlichung / Aktualisierung über GitHub
1. ZIP entpacken.
2. Im GitHub-Repository `gabelgruen` die neuen Dateien im Hauptverzeichnis hochladen und bestehende Dateien überschreiben (`index.html`, `sw.js`, `manifest.webmanifest`, `README.md` sowie den Ordner `icons`).
3. Änderungen committen. GitHub Pages aktualisiert die Website automatisch.
4. Auf dem iPhone die veröffentlichte Seite in Safari neu laden. Falls noch die alte Version angezeigt wird, Safari schließen und erneut öffnen; der Offline-Cache wurde auf v2 erhöht.

## Enthalten
- Mobile Oberfläche und Home-Bildschirm-Unterstützung
- Startseite mit Tagesplan
- Rezepte als zweispaltiges Raster auf kleinen Bildschirmen
- Wochenkalender, Vorschlag für Montag bis Freitag und Austausch einzelner Mahlzeiten
- Eine Mahlzeit je Datum und Mahlzeitentyp; vorhandene Mahlzeiten werden nicht still überschrieben
- Eigener Bereich für geschätzte Nährwerte
- Häufige Einkaufsprodukte (Startvorschläge plus lokal gezählte Wiederholung)
- Rezepte, Vorrat und Einkaufsliste lokal im Browser gespeichert

## Aktuelle Grenzen
- Daten bleiben lokal auf dem jeweiligen Gerät; es gibt noch keine Cloud-Synchronisierung oder Benutzerkonten.
- Ein Rezept-Link kann geöffnet werden, aber das automatische Auslesen beliebiger Rezept-Websites ist noch nicht aktiv. Viele Websites blockieren browserseitigen Zugriff (CORS); dafür brauchen wir später einen kleinen sicheren Server-/Proxy-Dienst.
- Wochenplanung erstellt einen unverbindlichen Zufallsvorschlag aus vorhandenen Rezepten. Sie ist noch keine KI-gestützte Planung und berücksichtigt noch nicht automatisch alle persönlichen Vorlieben.
- Nährwerte sind Schätzwerte.
- Angebots-/Preisvergleich ist absichtlich nicht enthalten.
