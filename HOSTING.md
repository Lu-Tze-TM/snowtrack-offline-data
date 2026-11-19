# SnowTrack Offline-Datenpakete

Öffentlicher Download-Host für Offline-Karten-Datenpakete der App
(Katalog: `app/src/main/assets/offline/regions.json` im Repo SnowTrack_Lu-Tze).

## Berlin (`berlin/`)

- Quelle: OpenStreetMap-Daten, BBBike-Extract Berlin (Stand 2026-11-15)
- Lizenz: **ODbL 1.0**, Attribution: **© OpenStreetMap-Mitwirkende**
- Dateien: `*.geojson.gz` (gzip -9 der unkomprimierten GeoJSON-Dateien).
  `manifest.json` enthält Größe + SHA-256 der **unkomprimierten** Dateien
  (so kann die App nach dem Dekomprimieren die Integrität prüfen).
- App-URLs: `https://raw.githubusercontent.com/Lu-Tze-TM/snowtrack-offline-data/main/berlin/<file>.geojson.gz`

Generiert mit `offline-data/tools/OsmToGeoJson.java` (SnowTrack_Lu-Tze).
