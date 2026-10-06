# Superbowl Castrop – Liga-Homepage

Kostenlose statische Fantasy-Football-Liga-Homepage auf GitHub Pages.

## Aktueller Aufbau
- `index.html` – komplette Website inklusive Design und Logik
- `data.js` – Liga-Historie, Manager, Regeln und Fallback-Standings
- `.nojekyll` – sorgt für eine saubere statische Auslieferung über GitHub Pages

## Sleeper Live-Daten
Die Website lädt aktuelle 2026-Daten direkt aus der öffentlichen Sleeper-API.

League ID: `1348415325250527232`

Wenn Sleeper nicht erreichbar ist, bleiben die hinterlegten Fallback-Daten sichtbar.

## GitHub Pages aktivieren
1. Repository öffnen
2. **Settings → Pages**
3. Unter **Build and deployment**: **Deploy from a branch**
4. Branch **main**
5. Ordner **/ (root)**
6. Speichern

Danach sollte die Website unter
`https://hecke-ff.github.io/Superbowl_Castrop/`
erreichbar sein.
