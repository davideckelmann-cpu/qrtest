# QR Check-in Web-App

Browserbasierter Prototyp für Veranstaltungen mit:

- Vorab-Auswahl von Fachforen, Programmpunkten und Verpflegung
- Event-Check-in am Veranstaltungstag
- Admin-Ansicht für Teilnehmerverwaltung und Live-Status

## Funktionen

### Teilnehmendenansicht
- Vorab-Auswahl 6 Wochen vor der Veranstaltung
- Auswahl von:
  - 1 Fachforum
  - bis zu 5 Programmpunkten
  - Verpflegung: Fleisch, vegetarisch, vegan
  - Lunchpaket
- separater Check-in am Veranstaltungstag

### Admin-Ansicht
- Dashboard mit Kennzahlen
- Teilnehmerliste
- manueller Check-in
- Diagnoseansicht

## Nutzung mit GitHub Pages

1. Neues Repository in GitHub anlegen
2. Datei `index.html` in das Hauptverzeichnis legen
3. Diese `README.md` hinzufügen
4. Datei `.nojekyll` hinzufügen
5. Optional Ordner `assets/` für Bilder und Icons anlegen
6. GitHub Pages in den Repository-Einstellungen aktivieren

## GitHub Pages aktivieren

- Repository öffnen
- **Settings** öffnen
- **Pages** auswählen
- Unter **Build and deployment**:
  - Source: **Deploy from a branch**
  - Branch: **main**
  - Folder: **/ (root)**

Danach ist die Seite unter der GitHub-Pages-URL erreichbar.

## Enthaltene Ansichten

- Admin-Ansicht
- Teilnehmendenansicht
- Vorab-Auswahl
- Event-Check-in

## Technischer Hinweis

Dies ist aktuell ein Frontend-Prototyp mit Demo-Daten.

Für den Produktivbetrieb sollten ergänzt werden:
- Backend/API
- Datenbankanbindung
- Token-Validierung
- Rollen und Rechte
- Persistenz für Vorabauswahl und Check-in

## Empfohlene nächste Schritte

- Backend anbinden
- Datenmodell finalisieren
- Hosting- und Sicherheitsmodell umsetzen
- Exporte für Catering, Fachforen und Anwesenheit ergänzen
