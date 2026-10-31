# Zeitsprung

Ein Musik-Zeitleisten-Spiel für ein Handy, das in der Runde herumgereicht wird.
Song hören, in die eigene Zeitleiste einordnen, Karten sammeln.

Spielen: einfach `index.html` im Browser öffnen (z. B. über GitHub Pages).
Die 30-Sekunden-Hörproben kommen über die iTunes Search API, ein Konto ist nicht nötig.
Die Songliste steht oben im `<script>` von `index.html` und lässt sich dort erweitern.

## Android-App (APK)

Die neueste APK gibt es hier: https://github.com/Nilnie/Zeitsprung/releases/download/app/Zeitsprung.apk

Auf dem Handy den Link öffnen, herunterladen, die Datei antippen und die Installation erlauben
("Aus dieser Quelle zulassen"). Bei jeder Änderung an `index.html` baut GitHub Actions
automatisch eine neue APK (Workflow `.github/workflows/android-apk.yml`, Android-Projekt in `android/`).
Neue Versionen lassen sich einfach über die alte installieren, der Spielstand bleibt erhalten.
