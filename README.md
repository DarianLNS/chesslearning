# ChessForge

ChessForge ist eine lokal laufende, deutschsprachige Trainingsoberfläche für Schachspieler. Die Anwendung enthält ein Dashboard, Trainingsplan, Fortschrittsübersicht, Einstellungen und eine echte spielbare Übung zur Brettorientierung.

## Starten

```bash
npm install
npm run dev
```

Danach die von Vite ausgegebene lokale URL im Browser öffnen. Für einen Produktions-Build:

```bash
npm run build
```

Die veröffentlichte Version ist unter https://darianlns.github.io/chesslearning/ erreichbar.

## Neue Aufgaben hinzufügen

Die Navigation und Beispielaufgaben liegen in `src/App.tsx`. Für eine neue Übung kann dort eine eigene Komponente ergänzt und im `App`-Routing unter dem passenden Bereich gerendert werden. Wiederverwendbare Farben, Layouts und responsive Regeln stehen in `src/styles.css`.

Der XP-Stand und das Theme werden bereits per `localStorage` gespeichert. Weitere Übungsstatistiken können mit demselben Muster persistiert werden.
