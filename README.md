# Paperino

**Paperino** ist ein freier, browserbasierter PDF-Editor, der vollständig ohne Server auskommt. Geöffnete Dokumente verlassen den Browser zu keinem Zeitpunkt.

> Aktuelle Version: **Alpha 0.1**

Live-Version: **<https://bacngaplays.github.io/Paperino/>** (GitHub Pages; die Adresse verwendet die exakte Schreibweise des Repository-Namens, also mit großem P)

## Funktionen

- PDFs öffnen, anzeigen und navigieren (Zoom, Seitenbreite, Tastaturkürzel, Miniaturansichten)
- Seiten löschen, extrahieren, ausschneiden, per Drag-and-Drop umsortieren und drehen
- Text an beliebiger Stelle einfügen, auch in Formulare ohne gesetzte Felder
- Markieren, Durchstreichen und freihändiges Zeichnen mit Farbwahl und Strichstärke
- Schwärzen mit Sicherheitsmodus: Beim Speichern wird die Seite als Bild neu aufgebaut, der Inhalt unter der Schwärzung wird dabei tatsächlich entfernt
- Rückgängig-Funktion und Speichern der bearbeiteten Datei als Download

## Nutzung

Die Anwendung besteht aus einer einzigen HTML-Datei:

1. `index.html` herunterladen oder das Repository klonen.
2. Die Datei in einem modernen Browser öffnen. Eine Internetverbindung ist nur zum Laden der beiden JavaScript-Bibliotheken erforderlich; die Dokumente selbst werden nicht übertragen.

Alternativ läuft die Anwendung über GitHub Pages unter `https://bacngaplays.github.io/Paperino/` (Veröffentlichungsquelle: Branch `gh-pages`).

## Technologie

- [PDF.js](https://mozilla.github.io/pdf.js/) (Apache-2.0) zum Rendern der Seiten
- [pdf-lib](https://pdf-lib.js.org/) (MIT) zum Aufbau und zur Bearbeitung der PDF-Dateien

## Versionierung

Paperino befindet sich im Alpha-Stadium. Jede neue Veröffentlichung (Push) erhöht die Versionsnummer im Format **Alpha 0.XXX**, also Alpha 0.1, Alpha 0.2 usw. Die aktuelle Version steht in der Titelleiste der Anwendung und in der Konstante `APP_VERSION` in der `index.html` sowie im Versionsverlauf unten.

| Version | Beschreibung |
| --- | --- |
| Alpha 0.1 | Erste Veröffentlichung: Seitenverwaltung, Lektorieren, Anonymisieren |

## Hinweise und Grenzen

- Passwortgeschützte PDFs werden nicht unterstützt.
- Eingefügter Text wird in der Schrift Helvetica gespeichert; der westeuropäische Zeichensatz wird unterstützt.
- Schwärzungen ohne Sicherheitsmodus verdecken den Inhalt nur optisch; der Text bleibt in der Datei enthalten. Für vertrauliche Dokumente sollte der Sicherheitsmodus aktiviert werden.

## Lizenz

Dieses Projekt steht unter der [GNU Affero General Public License 3.0](LICENSE). Beim Betrieb als Web-Dienst muss der Quellcode den Nutzerinnen und Nutzern zugänglich gemacht werden.
