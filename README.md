# 🚴‍♀️ Radreise Tracker

Interaktive Web-App zur Visualisierung einer Radreise quer durch Deutschland.
Zeigt Route auf OpenStreetMap, Statistiken, Kalorien, Höhenprofil und Achievements.


## 📱 So benutzt du die App

### GPX-Dateien aus Komoot exportieren

1. Komoot App öffnen → **Profil** → **Touren**
2. Eine aufgezeichnete Tour antippen
3. **"..."** (Drei-Punkte-Menü) → **"Als GPX-Datei exportieren"**
4. Die Datei speichern

### In den Tracker laden

1. Die Tracker-Website öffnen
2. GPX-Dateien unten in den Upload-Bereich ziehen (oder klicken)
3. Fertig — Route, Stats und Achievements aktualisieren sich automatisch

> **Hinweis:** Die GPX-Daten werden nur lokal im Browser verarbeitet.
> Beim Neuladen der Seite sind die Daten weg — das ist gewollt für die
> Demo-Version. In einer nächsten Iteration können wir Persistenz einbauen.

---

## 📊 Features

- **Interaktive Karte** — OpenStreetMap mit farbigen Routen pro Etappe
- **Statistiken** — Distanz, Fahrzeit, Höhenmeter, Ø Tempo, Reisetage
- **Kalorien-Tracking** — MET-basierte Berechnung mit Höhenbonus
- **Höhenprofil** — Gesamtprofil aller Etappen
- **23 Achievements** — Bronze, Silber, Gold mit lustigen Titeln
- **Fun-Facts-Ticker** — Pizza-Äquivalente, Erdumfang-%, Schneckentage...
- **Fortschrittsbalken** — Geschätzt auf ~900 km Gesamtroute
- **GPX-Import** — Drag & Drop, parst Koordinaten + Höhendaten + Dauer
- **Responsive** — Desktop und Mobile

---

## 🔧 Anpassungen

Die App ist eine einzige HTML-Datei. Alles lässt sich direkt editieren:

- **Geschätzte Gesamtdistanz** → im JS nach `est` suchen (aktuell 900 km)
- **Demo-Etappen** → Array `DEMO` im JS anpassen oder entfernen
- **Achievements** → Array `ACHS` — einfach neue hinzufügen
- **Kalorien-Gewicht** → im JS nach `68` suchen (aktuell 68 kg)

---

## 📁 Dateien

```
radreise-tracker/
├── index.html    ← Die komplette App (alles in einer Datei)
└── README.md     ← Diese Anleitung
```
