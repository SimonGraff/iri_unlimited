# 🚴‍♀️ Radreise Tracker

Interaktive Web-App zur Visualisierung einer Radreise quer durch Deutschland.
Zeigt Route auf OpenStreetMap, Statistiken, Kalorien, Höhenprofil und Achievements.

## 🚀 In 5 Minuten online stellen

### Schritt 1: GitHub Account

Falls du noch keinen hast → [github.com/signup](https://github.com/signup)

### Schritt 2: Neues Repository erstellen

1. Gehe zu [github.com/new](https://github.com/new)
2. **Repository name:** `radreise-tracker` (oder was du willst)
3. **Public** auswählen (muss public sein für GitHub Pages)
4. **"Add a README file"** → Haken setzen
5. Klick **"Create repository"**

### Schritt 3: index.html hochladen

1. Im neuen Repository auf **"Add file"** → **"Upload files"** klicken
2. Die Datei `index.html` aus diesem Ordner hochladen (Drag & Drop)
3. Unten auf **"Commit changes"** klicken

### Schritt 4: GitHub Pages aktivieren

1. Im Repository auf **"Settings"** (Zahnrad-Tab oben)
2. Links im Menü auf **"Pages"**
3. Unter **"Source"** → **"Deploy from a branch"**
4. Branch: **"main"**, Folder: **"/ (root)"**
5. Klick **"Save"**
6. Warte 1-2 Minuten, dann steht oben die URL:

```
https://DEIN-USERNAME.github.io/radreise-tracker/
```

**Das war's!** Diese URL kannst du deiner Partnerin schicken.

---

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
