# Paperino

**Paperino** ist ein freier, browserbasierter PDF-Editor, der vollständig ohne Server auskommt. Geöffnete Dokumente verlassen den Browser zu keinem Zeitpunkt.

> Aktuelle Version: **Alpha 0.3**

Live-Version: **<https://bacngaplays.github.io/Paperino/>** (GitHub Pages; die Adresse verwendet die exakte Schreibweise des Repository-Namens, also mit großem P)

## Funktionen

- PDFs öffnen, anzeigen und navigieren (Zoom, Seitenbreite, Tastaturkürzel, Miniaturansichten)
- Fortlaufender Seitenlauf: alle Seiten untereinander anzeigen und durch das gesamte Dokument scrollen (Abschaltbar unter „Ansicht“)
- Seiten löschen, extrahieren, ausschneiden, per Drag-and-Drop umsortieren und drehen
- Text an beliebiger Stelle einfügen und direkt im Dokument schreiben, auch in Formulare ohne gesetzte Felder
- Textgebundenes Markieren, Durchstreichen und Unterstreichen direkt am Originaltext
- Schwärzen als Rechteck oder für markierten Text; mit Sicherheitsmodus wird die Seite beim Speichern als Bild neu aufgebaut, der Inhalt unter der Schwärzung wird dabei tatsächlich entfernt und ist danach nicht mehr markierbar
- Freihändiges Zeichnen mit Stift und Textmarker (Farb- und Strichstärkenwahl)
- Formen einfügen: Rechteck, Ellipse, Dreieck, Raute, Stern, Linie und Pfeil
- Jedes Werkzeug erstellt genau ein Element und schaltet danach automatisch auf Auswahl zurück
- Alle erstellten Elemente lassen sich anklicken, verschieben und in der Größe ändern (Textfelder skalieren die Schriftgröße, Linien und Pfeile über die Endpunkte)
- Kommentieren: Kommentare an markiertem Text oder an einer Stelle, direkt im Dokument schreibbar; beim Speichern werden sie als echte PDF-Notizen abgelegt und erscheinen auch in anderen PDF-Programmen
- Ein-Schritt-Rückgängig für alle Aktionen und Speichern der bearbeiteten Datei als Download

## Nutzung

Die Anwendung besteht aus einer einzigen HTML-Datei:

1. `index.html` herunterladen oder das Repository klonen.
2. Die Datei in einem modernen Browser öffnen. Eine Internetverbindung ist nur zum Laden der beiden JavaScript-Bibliotheken erforderlich; die Dokumente selbst werden nicht übertragen.

Alternativ läuft die Anwendung über GitHub Pages unter `https://bacngaplays.github.io/Paperino/` (Veröffentlichungsquelle: Branch `main`, Ordner `/(root)`).

## Technologie

- [PDF.js](https://mozilla.github.io/pdf.js/) (Apache-2.0) zum Rendern der Seiten
- [pdf-lib](https://pdf-lib.js.org/) (MIT) zum Aufbau und zur Bearbeitung der PDF-Dateien

## Versionierung

Paperino befindet sich im Alpha-Stadium. Jede neue Veröffentlichung (Push) erhöht die Versionsnummer im Format **Alpha 0.XXX**, also Alpha 0.1, Alpha 0.2 usw. Die aktuelle Version steht in der Titelleiste der Anwendung und in der Konstante `APP_VERSION` in der `index.html` sowie im Versionsverlauf unten.

| Version | Beschreibung |
| --- | --- |
| Alpha 0.1 | Erste Veröffentlichung: Seitenverwaltung, Lektorieren, Anonymisieren |
| Alpha 0.2 | Fortlaufender Seitenlauf, textgebundene Werkzeuge, Formen, Stift und Textmarker, Kommentieren mit PDF-Notizen, Ein-Schritt-Rückgängig, Sicherheitsmodus standardmäßig aktiv |
| Alpha 0.3 | Interaktive Elemente: verschieben und Größe ändern, direkte Texteingabe im Dokument, textgebundenes Schwärzen, Einmal-Aktivierung der Werkzeuge |

## Hinweise und Grenzen

- Passwortgeschützte PDFs werden nicht unterstützt.
- Eingefügter Text wird in der Schrift Helvetica gespeichert; der westeuropäische Zeichensatz wird unterstützt.
- Schwärzungen ohne Sicherheitsmodus verdecken den Inhalt nur optisch; der Text bleibt in der Datei enthalten. Der Sicherheitsmodus ist daher standardmäßig aktiviert.

## Lizenz

Dieses Projekt steht unter der [GNU Affero General Public License 3.0](LICENSE). Beim Betrieb als Web-Dienst muss der Quellcode den Nutzerinnen und Nutzern zugänglich gemacht werden.
