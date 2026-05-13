# Route66 GitHub Paket v77 · TV Dokus · City Guide · Online/Offline App

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

Die Cache-Version wurde auf `route66-trip-v77-city-guide` gesetzt. Falls auf dem Smartphone noch alte Inhalte erscheinen: App schließen, Seite neu laden oder Browser-/PWA-Cache löschen.

## Dateien

- `index.html` – App/UI
- `routeData.v35.js` – Tagesplan und Fahrplan
- `route66MustStops.js` – Must-Stops und Highlights
- `musicBars.js` – Musik-/Bar-Empfehlungen
- `manifest.webmanifest` – PWA-Metadaten
- `service-worker.js` – Offline-Cache
- `icon-192.png`, `icon-512.png` – App-Icons


## Neu in v77

- Viele neue kuratierte Kartenpunkte für **Sehenswürdigkeiten, Restaurants, MusicBars, Bars, Rooftops und Nightlife**.
- Neue Empfehlungen u.a. für Chicago, St. Louis, Tulsa, Lawton/Medicine Park und Austin.
- Keine Gibson/Fender-Store-Logik, Fokus auf echte Orte: Food, Bars, Musik, Viewpoints und Route-66-Feeling.
- Karten- und Listenansicht zeigen jetzt Badges wie **Pflicht**, **Sunset Spot**, **Live Music**, **BBQ**, **Cocktails**, **Best at Night**.
- 360-/StreetView-Links wurden für Orte mit Koordinaten ergänzt.
- Google-Maps-Popups zeigen beste Besuchszeit und Zusatzinfos.
- Die TV-Dokus-Sektion wurde als Inspirations-/Preview-Bereich erweitert.
- Browser-Titel und Service-Worker-Cache auf v77 aktualisiert.
