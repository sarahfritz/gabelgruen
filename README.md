# Gabelgrün – mobile Web-App

Diese Version ist bewusst ohne Angebots-/Preisvergleich aufgebaut. Die Funktion kann später ergänzt werden.

## Enthalten
- mobile-first Oberfläche für iPhone und Computer
- als PWA für den Home-Bildschirm vorbereitet
- Heute / Tagesübersicht
- Rezeptsuche und Filter
- Rezeptdetails mit Portionsanpassung
- eigene Rezepte speichern und löschen
- Essensplan nach Datum und Mahlzeit
- Nährwertübersicht als Schätzung
- Vorrat mit Zutaten und Mengen
- Einkaufsliste
- automatische Übernahme fehlender Rezeptzutaten in die Einkaufsliste
- persönliche Einstellungen
- Datenexport und -import als Sicherung
- Offline-Grundgerüst per Service Worker

## Aktueller Stand
Die Daten dieser ersten Online-Version werden noch lokal im jeweiligen Browser gespeichert. Das bedeutet: iPhone und Computer teilen die Daten noch nicht automatisch.

Die Cloud-Synchronisierung ist der nächste technische Schritt. Der Angebots-/Preisvergleich für SPAR, Lidl und HOFER wird bewusst erst danach ergänzt.

## Veröffentlichung mit GitHub Pages
1. Repository auf GitHub erstellen, z. B. `gabelgruen`.
2. Die Dateien aus diesem Ordner in das Hauptverzeichnis des Repositorys hochladen. Wichtig: `index.html`, `manifest.webmanifest`, `sw.js` und den Ordner `icons`.
3. In GitHub: Settings → Pages → Build and deployment → Deploy from a branch → Branch `main` → Folder `/ (root)` → Save.
4. Die von GitHub angezeigte Website-Adresse in Safari auf dem iPhone öffnen.
5. In Safari: Teilen → Zum Home-Bildschirm → Hinzufügen.

Danach lässt sich Gabelgrün direkt über das Home-Screen-Symbol öffnen.
