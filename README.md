# Route66 GitHub Paket v79 · MAP COMPLETE FREE

Diese Version erweitert die kostenlose OpenStreetMap/Leaflet-Version so, dass alle wichtigen Listen-Kategorien auf der Karte erscheinen:

- Top Highlights
- MusicBars
- Hotels
- Food
- Distilleries
- Route66 Stops
- Sonstiges

## Wichtig

Es wird weiterhin **keine Google Maps JavaScript API**, **keine Places API** und **kein Geocoding API-Key** verwendet.

Google-Maps-Buttons bleiben als normale externe Links erhalten. Das verursacht keine Google-Cloud-API-Kosten.

## Änderungen v79

- Alle Orte ohne vorhandene lokale Koordinaten bekommen jetzt lokale Fallback-Koordinaten.
- Hotels werden als größere Basecamp-Marker dargestellt.
- Marker-Farben richten sich nach der finalen Kategorie: Hotels, Top Highlights, MusicBars, Food, Distilleries, Route66 Stops und Sonstiges.
- Layer-Filter zeigen jetzt zuverlässig alle Kategorien auf der Karte.
- Popups zeigen an, wenn eine Koordinate lokal geschätzt wurde.
- Cache-Version auf `route66-trip-v79-map-complete` erhöht.

## Genauigkeit der Karte

Orte mit hinterlegten Koordinaten bleiben exakt. Für Einträge, die bisher nur Google-Maps-Links oder Suchtexte hatten, nutzt die App eine lokale Koordinatenliste und als letzte Stufe einen lokalen Stadt-/Etappen-Fallback. Dadurch erscheinen wirklich alle Einträge auf der Karte, ohne kostenpflichtige Geocoding-API.

## Nutzung

1. Alle Dateien aus diesem Paket ins GitHub-Repo kopieren und bestehende Dateien ersetzen.
2. GitHub Pages neu laden.
3. Auf dem Smartphone einmal online öffnen, damit der neue Service Worker gespeichert wird.
4. Falls noch alte Inhalte erscheinen: PWA schließen, Browser/PWA-Cache löschen oder Service Worker unregister.
