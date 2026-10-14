# Bauchbuch

Tagebuch für Essen, Bauch-Symptome und Weinen. Alle Daten bleiben im Browser-Speicher (IndexedDB) auf dem Gerät.

## Aufs iPhone bringen

1. Die Dateien in diesem Ordner auf einen HTTPS-Host legen, z. B. GitHub Pages:
   neues Repository anlegen, alle Dateien hochladen, unter Settings → Pages den Branch `main` / Ordner `/` wählen.
2. Die Pages-Adresse auf dem iPhone in **Safari** öffnen.
3. Teilen → „Zum Home-Bildschirm“.
4. Ab jetzt Bauchbuch nur noch über das Symbol auf dem Home-Bildschirm öffnen.

Wichtig: Die Daten gehören zu genau dieser Installation. Wer die App vom Home-Bildschirm löscht, löscht auch die Einträge.
Deshalb unter „Daten“ ab und zu ein Backup in die Dateien-App sichern.

## Updates

Nach Änderungen an `index.html` die Konstante `CACHE` in `sw.js` hochzählen (z. B. `bauchbuch-v2`), damit das iPhone die neue Version lädt.
