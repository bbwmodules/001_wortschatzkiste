# Flashcards Project

Dies ist ein Minimalbeispiel für digitale Lernkärtchen mit GitHub Pages.

## Nutzung
1. Repository auf GitHub erstellen und Dateien hochladen.
2. GitHub Pages in den Settings aktivieren (Branch: main, Root).
3. Seite öffnen: https://<dein-user>.github.io/<repo>/
4. Thema wählen und loslegen.

## Themen hinzufügen
- Neue JSON-Datei unter /data anlegen.
- Struktur siehe `networking.json`.

Die Datenstruktur wird  dynamisch angebunden:

### Ohne URL-Themenbereich:

Auswahlfeld zBsp für _html_css, java, networking_ <br/>
Danach Auswahlfeld mit den topic-Texten der JSON-Dateien

### Mit URL-Themenbereich

z. B.: http://localhost:8000/?topic=java

Nur das Dateiauswahlfeld wird angezeigt.<br/>
Die ausgewählte JSON-Datei wird automatisch geladen und für Flashcards sowie Übungen verwendet.
