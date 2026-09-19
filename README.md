# Die Wort-Schatz-Kiste

Zu verschiedenen IT-Themen und auf verschiedene Arten und Weisen können Begriffe und Wörter spielersich sich angeeignet werden.

## Nutzung
1. Repository auf GitHub erstellen und Dateien hochladen.
2. GitHub Pages in den Settings aktivieren (Branch: master, Root).
3. Seite öffnen: https://<dein-user>.github.io/<repo>/
4. Thema wählen und loslegen.

## Themen hinzufügen
- Neue JSON-Datei unter /data/<thema> anlegen.
- Struktur siehe `networking.json`.
- Den Dateinamen zusätzlich im `dataCatalog` in `index.html` eintragen.

Die Datenstruktur wird über einen Katalog in `index.html` angebunden, weil GitHub Pages keine Verzeichnislistings für `/data/` bereitstellt:

### Ohne URL-Themenbereich:

Auswahlfeld erscheint zu den Themen: zBsp für _html_css, java, networking_ <br/>
Danach Auswahlfeld mit den topic-Texten der JSON-Dateien

### Mit URL-Themenbereich

z. B.: http://localhost:8000/?topic=java

Nur das Dateiauswahlfeld wird angezeigt.<br/>
Die ausgewählte JSON-Datei wird automatisch geladen und für Flashcards sowie Übungen verwendet.
