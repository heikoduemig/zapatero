# Route66 GitHub Paket v76 · Online/Offline App

Diese Version ist als **eine einzige PWA-App** gebaut: online mit Karte und externen Google-Maps-Links, offline mit lokal gespeicherten Tagesdaten, Hotels, Etappen, Highlights und MusicBars.

## Nutzung

1. Alle Dateien aus diesem ZIP in das GitHub-Repo kopieren und bestehende Dateien ersetzen.
2. GitHub Pages neu laden.
3. Seite einmal online öffnen, damit der Service Worker die App-Dateien speichert.
4. Auf dem Smartphone als App installieren:
   - iPhone/Safari: Teilen → „Zum Home-Bildschirm“
   - Android/Chrome: Menü → „App installieren“

## Offline verfügbar

- Tagesplan
- Etappen, Abfahrten & Ankünfte
- Hotels
- Highlights
- MusicBars
- lokale Route-Daten
- App-Layout und Icons

## Online benötigt

- Google Maps Karte
- Google-Maps-Navigation
- externe Links

Wenn die App offline ist, wird die Karte automatisch durch einen Hinweis ersetzt. Sobald wieder Internet vorhanden ist, funktioniert die Karte wieder nach Reload bzw. automatisch je nach Browser.

## Wichtig bei Updates

Die Cache-Version wurde auf `route66-trip-v76-icon-mobile-maps` gesetzt. Falls auf dem Smartphone noch alte Inhalte erscheinen: App schließen, Seite neu laden oder Browser-/PWA-Cache löschen.

## Dateien

- `index.html` – App/UI
- `routeData.v35.js` – Tagesplan und Fahrplan
- `route66MustStops.js` – Must-Stops und Highlights
- `musicBars.js` – Musik-/Bar-Empfehlungen
- `manifest.webmanifest` – PWA-Metadaten
- `service-worker.js` – Offline-Cache
- `icon-192.png`, `icon-512.png` – App-Icons


## Änderungen v76

- App-Icons optisch nachgeschärft: stärkere Linien, bessere Safe Area, zentriertere Typografie und mehr Luft bei „USA“.
- Mobile Schnellnavigation um einen prominenten Button „📍 Google Maps Route öffnen“ ergänzt.
- Browser-Titel und Service-Worker-Cache auf v76 aktualisiert.
