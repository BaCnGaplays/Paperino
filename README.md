# Paperino

**Paperino** ist ein freier, browserbasierter PDF-Editor, der vollständig ohne Server auskommt. Geöffnete Dokumente verlassen den Browser zu keinem Zeitpunkt.

> Aktuelle Version: **Alpha 0.7**

Live-Version: **<https://bacngaplays.github.io/Paperino/>** (GitHub Pages; die Adresse verwendet die exakte Schreibweise des Repository-Namens, also mit großem P)

## Funktionen

- PDFs öffnen, anzeigen und navigieren (Zoom, Seitenbreite, 100-Prozent-Ansicht, Ein- und Doppelseitenansicht, fortlaufender Bildlauf, Tastaturkürzel, Miniaturansichten)
- Ansichtshilfen: Lineale mit Zentimeterinteilung und Gitternetzlinien, ein- und ausblendbar über den Reiter Ansicht
- Seitenleiste mit drei Ansichten: Seiten, Inhaltsverzeichnis des Dokuments (Navigation zu den Verzeichnismarken) und Lesezeichen; Leiste vollständig ein- und ausblendbar
- Seiten löschen, extrahieren, ausschneiden, per Drag-and-Drop umsortieren und drehen
- Textfelder mit Schriftartwahl (Helvetica, Times New Roman, Courier New) und Schriftgröße als Dropdown mit frei eingebbarem Wert (8 bis 72 Punkt)
- Textformatierung wie in einer Textverarbeitung: Fett, Kursiv, Unterstrichen mit Unterstreichungsarten (einfach, doppelt, gepunktet, gestrichelt, wellig), Durchgestrichen, Hoch- und Tiefstellen; Piktogramm-Schaltflächen mit Schriftproben, zweizeilig angeordnet
- Farbwahlmenü mit Standardfarben-Kacheln, Optionen „Keine Füllung“ und „Keine Kontur“, und einem eigenen Bereich „Weitere Farben“ (RGB, HSL und Hex über die Farbauswahl des Browsers), bei Füllungen zusätzlich mit Transparenzregel, bei Konturen mit Strichstärkenwahl
- Textfelder mit Fülleffekt (inklusive Transparenz) und Formkontur; die Größe des Textfelds ändert den Bereich, nicht die Schriftgröße
- LaTeX-Formeln über eine Formel-Schaltfläche (Brüche, Wurzeln, Hoch- und Tiefstellen, griechische Buchstaben, Symbole), beim Speichern als eingebettetes Bild abgelegt
- Pfeile mit einstellbaren Pfeilspitzen: ohne, linke, rechte oder beide Spitzen, offen oder gefüllt
- Strichstärken in Punkten (0,25 bis 6 Pt) und Stricharten: Unilinie, runder Punkt, viereckiger Punkt, gestrichelt, Strichpunktmuster, langer Strich
- Formen und Textfelder drehen: runde Eckgriffe, Seitenbalken zum einseitigen Ziehen, Drehgriff oben, Verschieben in Punkt-Schritten über Richtungspfeile
- Textgebundenes Markieren, Durchstreichen und Unterstreichen direkt am Originaltext
- Schwärzen als Rechteck oder für markierten Text; mit Sicherheitsmodus wird die Seite beim Speichern als Bild neu aufgebaut, der Inhalt unter der Schwärzung wird dabei tatsächlich entfernt und ist danach nicht mehr markierbar
- Freihändiges Zeichnen mit Stift und Textmarker (Farb- und Strichstärkenwahl)
- Formen einfügen: Rechteck, Ellipse, Dreieck, Raute, Stern, Linie und Pfeil
- Kommentaren: Kommentare an markiertem Text oder an einer Stelle; die Kommentarleiste erscheint automatisch beim ersten Kommentar, ist standardmäßig ausgeblendet und lässt sich über das Kreuz schließen und über die Ansicht wieder öffnen; beim Speichern werden Kommentare als echte PDF-Notizen abgelegt
- Lesezeichen pro Dokument anlegbar (lokal im Browser gespeichert)
- Statusleiste unten mit Bibliothekenstatus und Seitenanzeige
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
| Alpha 0.4 | Farbschema an der Grundfarbe #6F003C (Bordeauxrot) ausgerichtet |
| Alpha 0.5 | Kontextreiter „Textfeld“ (Schriftgröße, Farbe, Fett, Kursiv, LaTeX-Formeln) und „Formformat“ (Kontur, Strichstärke, Füllung), ein- und ausklappbare Fenster für Seiten und Kommentare, Lesezeichen, Statusleiste unten, Korrektur der Textdarstellung bei Drehung und Zoom, präzisere Textauswahl |
| Alpha 0.6 | Textfeldformatierung im Stil einer Textverarbeitung (Schriftarten, Unterstreichungsarten, Durchstreichen, Hoch- und Tiefstellen, Groß-/Kleinschreibung, Farbwahlmenü), Formeln über Schaltfläche, Textfelder mit Fülleffekt und Kontur, Größenänderung ohne Schriftskalierung, Pfeilspitzen, Strichstärken in Punkt und Stricharten, Drehgriff und Seitenbalken, korrigierte Darstellung von Anmerkungen bei Zoom und hohen Auflösungen, Kommentarleiste automatisch, Seitenleiste mit Inhaltsverzeichnis, Ansichtsbuttons, Lineale und Gitternetz |
| Alpha 0.7 | Korrektur der ein- und ausblendbaren Leisten (Seitenleiste und Kommentarleiste lassen sich nun tatsächlich schließen, Kommentarleiste standardmäßig ausgeblendet), Farbwahlmenü neu aufgebaut (Standardfarben-Kacheln, „Keine Füllung“/„Keine Kontur“ als Kachel, „Weitere Farben“ als eigener Bereich mit Transparenz bei Füllung und Strichstärkenwahl bei Konturen), Formatleiste zweizeilig mit Piktogrammen und Schriftproben, Schriftgröße als Dropdown mit frei eingebbarem Wert, Schreibweise-Umwandlung und Größenwippen entfernt, Hinweise auf Tooltips umgestellt |

## Hinweise und Grenzen

- Passwortgeschützte PDFs werden nicht unterstützt.
- Eingefügter Text wird in den Schriften Helvetica, Times New Roman oder Courier New gespeichert; der westeuropäische Zeichensatz wird unterstützt.
- LaTeX-Formeln werden beim Speichern als eingebettetes Bild abgelegt, da die PDF-Standardschriften keine mathematischen Symbole enthalten.
- Wellige Unterstreichungen werden beim Speichern als gerade Linie angenähert; gedrehter Text wird beim Speichern an gleicher Stelle ohne Drehung abgelegt.
- Schwärzungen ohne Sicherheitsmodus verdecken den Inhalt nur optisch; der Text bleibt in der Datei enthalten. Der Sicherheitsmodus ist daher standardmäßig aktiviert.

## Lizenz

Dieses Projekt steht unter der [GNU Affero General Public License 3.0](LICENSE). Beim Betrieb als Web-Dienst muss der Quellcode den Nutzerinnen und Nutzern zugänglich gemacht werden.
