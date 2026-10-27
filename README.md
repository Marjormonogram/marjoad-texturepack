# Marjoad Texturepack

Test-Texturepack für die Marjoad-Update-Mod.

- `pack/` – Quelldateien des Packs
- `update.json` – Manifest, das die Mod beim Server-Join abfragt
- Die fertigen ZIPs liegen unter **Releases**

## Neue Version freigeben
1. Dateien in `pack/` ändern
2. ZIP bauen (Inhalt von `pack/`, nicht der Ordner selbst)
3. Release `vX.Y.Z` mit `MarjoadPack-X.Y.Z.zip` anlegen
4. `version`, `url`, `sha256` und `changelog` in `update.json` anpassen und pushen
