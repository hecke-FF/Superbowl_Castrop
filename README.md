# Superbowl Castrop – Liga-Homepage

Statische, kostenlose Fantasy-Football-Liga-Homepage für GitHub Pages.

## Dateien
- `index.html` – komplette Website
- `styles.css` – Design und Responsive Layout
- `data.js` – historische Liga-Daten und Fallback-Standings
- `app.js` – Darstellung + Live-Anbindung an Sleeper
- `.nojekyll` – verhindert unnötige Jekyll-Verarbeitung auf GitHub Pages

## Kostenlos auf GitHub Pages veröffentlichen
1. Auf GitHub ein neues **öffentliches Repository** erstellen, z. B. `Superbowl_Castrop`.
2. Die Web-Dateien liegen direkt im Repository.
3. In GitHub: **Settings → Pages**.
4. Unter **Build and deployment**: `Deploy from a branch` wählen.
5. Branch `main`, Ordner `/ (root)` auswählen und speichern.
6. Danach ist die Seite unter `https://hecke-ff.github.io/Superbowl_Castrop/` erreichbar.

## Sleeper Live-Daten
Die Seite nutzt die öffentliche Sleeper-API direkt im Browser. Dafür ist kein Server und kein API-Key nötig.

League ID 2026: `1348415325250527232`

Wenn Sleeper nicht erreichbar ist, zeigt die Seite automatisch die zuletzt hinterlegten Fallback-Daten.

## Historische Daten aktualisieren
Historische Liga-Daten stehen in `data.js`. Dadurch können Regeln, Champions und Endplatzierungen saisonweise gepflegt werden, ohne HTML umzubauen.
