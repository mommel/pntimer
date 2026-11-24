# PN Timer – Plage Noire 2026 Gruppen-App

Progressive Web App für das Plage Noire Festival 2026 (20.–21.11.2026) – ohne Server.

**App:** https://mommel.github.io/pntimer/

## Funktionen
- Timetable (Do–Sa, alle Bühnen inkl. Lesungen) mit Herz-Voting
- Gruppen-Sync per kurzem Code (z. B. über WhatsApp) – kein Backend
- Heatmap und Gruppenplan: wer will wann wohin, Überschneidungen mit Mehrheit ★
- Erinnerungen X Minuten vorher (solange die App offen ist) und Kalender-Export (.ics) mit Alarm
- Eigene Geländeskizze (SVG) mit Bühnen-Markierung, Symbol-Filter und „Was läuft gerade auf welcher Bühne“
- Offline-fähig dank Service Worker

## Installation auf dem iPhone
Link in Safari öffnen → **Teilen** → **Zum Home-Bildschirm**. Benachrichtigungen funktionieren nur in der installierten App (iOS 16.4+).

## Hinweise
- Endzeiten sind aus den Balkenlängen des offiziellen Timetables abgeleitet.
- Die Reihenfolge des `RAW`-Arrays in `index.html` ist Teil des Sync-Codes – neue Einträge nur anhängen.
- Nach Änderungen die Cache-Version in `sw.js` (`pn26-vX`) hochzählen, damit installierte Apps das Update laden.
- Inoffizielles Fan-Tool, nicht vom Veranstalter.
