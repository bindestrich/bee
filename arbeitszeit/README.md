# Arbeitszeit – Zeiterfassung für den Außendienst

Web-App fürs Handy, die auch offline läuft. Die Daten werden nur lokal auf dem Gerät gespeichert.

## Funktionen
- Buttons für **Hinfahrt**, **Arbeit im Store**, **Pause**, **Heimfahrt** und **Feierabend**. Ein Tipp beendet die laufende Tätigkeit und startet die neue.
- Fahrzeit zählt als Arbeitszeit, Pausen zählen nicht.
- **Tagesart** wählen:
  - **Tagestour** 🏠→🏬→🏠
  - **Anreise** 🏠→🏬→🛏
  - **Vor Ort** 🛏→🏬→🛏
  - **Abreise** 🛏→🏬→🏠

  Nach einem Anreise- oder Vor-Ort-Tag schlägt die App automatisch „Abreise“ vor.
- **Heimfahrtdauer** bei Tagestour/Abreise. Die App rechnet aus, wann du spätestens losfahren musst, damit du bei 8:30 h zu Hause bist.
- Erinnerung per Ton, Vibration und Benachrichtigung, solange die App geöffnet ist.
- Zusätzlich kannst du die Erinnerung als **Kalender-Wecker (.ics)** eintragen. Der klingelt auch bei gesperrtem Handy.
- Verlauf pro Monat. Tage lassen sich korrigieren oder nachtragen.
- Export als **Excel (CSV)** oder **PDF** (Druckdialog, dann „Als PDF sichern“).
- Datensicherung als JSON-Datei zum Speichern und Laden.

## Starten
Die App muss über HTTPS erreichbar sein, zum Beispiel per GitHub Pages:
Repository → Settings → Pages → Branch wählen → `/(root)`. Danach ist sie erreichbar unter
`https://<benutzer>.github.io/bee/arbeitszeit/`.

Auf dem Handy öffnen und dann:
- **iPhone (Safari):** Teilen → „Zum Home-Bildschirm“
- **Android (Chrome):** ⋮ → „App installieren“ / „Zum Startbildschirm hinzufügen“

Lokal testen: `python3 -m http.server` im Ordner starten und `http://localhost:8000` öffnen.
