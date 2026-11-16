# Arbeitszeit – Zeiterfassung für den Außendienst

Web-App fürs Handy, die auch offline läuft. Die Daten werden nur lokal auf dem Gerät gespeichert.

## So funktioniert's
- **Ein großer Knopf für den nächsten Schritt:** „Ich fahre los“ → „Im Store angekommen“ → „Ich fahre nach Hause“ → „Zuhause angekommen“.
- **Pause** und **Nächster Store** gibt es jederzeit als kleine Knöpfe.
- **Fortschrittsring:** Er zeigt die Arbeitszeit inkl. Fahrt im Verhältnis zum Tagesziel (Standard 8:30 Std.). Pausen zählen nicht mit.
- **Tagesart:**
  - **Hin und zurück**
  - **Hinfahren & übernachten**
  - **Ganzer Tag vor Ort**
  - **Heimreise**

  Nach einer Übernachtung schlägt die App am nächsten Tag automatisch „Heimreise“ vor.
- **Fahrzeit nach Hause einstellen:** Die App sagt dir, wann du spätestens losfahren musst.
- **Erinnerung:**
  - Ton, Vibration und Benachrichtigung bei geöffneter App
  - zusätzlich als **Wecker im Kalender**

## Nachweis
- **Excel (CSV)** und **PDF** pro Monat
- **Kalender:** Jeder Arbeitstag wird als Termin gespeichert, von Beginn bis Feierabend. Der Termin enthält:
  - Ort bzw. Notiz
  - Stunden
  - alle Einzelzeiten

  Das geht direkt nach Feierabend, pro Tag im Verlauf oder für den ganzen Monat.
- **Datensicherung** als JSON-Datei (Einstellungen)

## Starten
Erreichbar über GitHub Pages: `https://bindestrich.github.io/bee/arbeitszeit/`

Auf dem Handy öffnen und zum Home-Bildschirm hinzufügen:
- **iPhone:** Safari → Teilen → „Zum Home-Bildschirm“
- **Android:** Chrome → ⋮ → „App installieren“
