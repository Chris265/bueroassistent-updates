# Büro-Gehirn — Update-Manifest (öffentlich)

Dieses **öffentliche** Repo enthält nur eine Datei: `update_manifest.json`.
Sie verrät der installierten App, welche Version aktuell ist (Versionsnummer +
Release-Notizen) — **kein Code, keine Geheimnisse**. Die eigentlichen Programm-
Images liegen weiterhin **privat** in der GitHub Container Registry.

Die App fragt die Roh-URL dieser Datei ab (`UPDATE_MANIFEST_URL`):
https://raw.githubusercontent.com/Chris265/bueroassistent-updates/main/update_manifest.json

Aktualisiert wird die Datei automatisch durch `scripts/release.ps1` im Hauptprojekt.
