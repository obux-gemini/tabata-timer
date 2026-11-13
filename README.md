# Tabata Timer

Intervall-Timer fürs iPhone als Web-App: klassisches Tabata (20/10 × 8) und eigene Timer aus beliebigen Intervallen.

**App öffnen:** https://obux-gemini.github.io/tabata-timer/

## Aufs iPhone holen

1. Link in Safari öffnen
2. Teilen → **Zum Home-Bildschirm**
3. Ab dann startet der Timer wie eine App und funktioniert auch offline

## Funktionen

- Bildschirmfarbe je Phase (Training rot, Pause türkis, Countdown gelb, fertig grün)
- Pieptöne in den letzten 3 Sekunden und deutsche Sprachansage
- Tabata-Einstellungen: Training, Pause, Runden, Sätze, Satzpause, Vorlagen
- Eigene Timer: benannte Intervalle, Reihenfolge ändern, Wiederholungen
- Bildschirm bleibt während des Trainings an
- Einstellungen und Timer werden lokal im Browser gespeichert

Eine einzige `index.html` ohne Abhängigkeiten, dazu Manifest, Icons und ein Service Worker für den Offline-Betrieb.
