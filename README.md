# Route66 GitHub Paket v76 · TV Dokus · Online/Offline App

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
- TV Dokus
- lokale Route-Daten
- App-Layout und Icons

## Online benötigt

- Google Maps Karte
- Google-Maps-Navigation
- externe Links

Wenn die App offline ist, wird die Karte automatisch durch einen Hinweis ersetzt. Sobald wieder Internet vorhanden ist, funktioniert die Karte wieder nach Reload bzw. automatisch je nach Browser.

## Wichtig bei Updates

Die Cache-Version wurde auf `route66-trip-v76-tv-dokus` gesetzt. Falls auf dem Smartphone noch alte Inhalte erscheinen: App schließen, Seite neu laden oder Browser-/PWA-Cache löschen.

## Dateien

- `index.html` – App/UI
- `routeData.v35.js` – Tagesplan und Fahrplan
- `route66MustStops.js` – Must-Stops und Highlights
- `musicBars.js` – Musik-/Bar-Empfehlungen
- `manifest.webmanifest` – PWA-Metadaten
- `service-worker.js` – Offline-Cache
- `icon-192.png`, `icon-512.png` – App-Icons


## Neu in v76

- Neue einklappbare Sektion **TV Dokus** ganz unten in der App.
- Direkte Links zu TV-/Mediathek-/Sender- und Doku-Seiten.
- Erweiterung um Kuriositäten und Sehenswürdigkeiten entlang Chicago → St. Louis → Tulsa → Lawton → Austin.
- Bottom-Navigation um **TV** ergänzt.
- Browser-Titel und Service-Worker-Cache auf v76 aktualisiert.


## v79 · TV Dokus restored

Die TV-Dokus-Karte ist wieder ganz unten eingebaut. Der Titel lautet ohne Icon: „TV Dokus“.


## v80 · TV Dokus + offizielle YouTube Clips

Die TV-Dokus-Karte enthält jetzt zusätzliche YouTube-Buttons nur für offizielle bzw. institutionelle Quellen. Private Reuploads wurden bewusst nicht aufgenommen.
