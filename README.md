# Paperino

**Paperino** ist ein freier, browserbasierter PDF-Editor, der vollständig ohne Server auskommt. Geöffnete Dokumente verlassen den Browser zu keinem Zeitpunkt.

> Aktuelle Version: **Alpha 0.17**

Live-Version: **<https://bacngaplays.github.io/Paperino/>** (GitHub Pages; die Adresse verwendet die exakte Schreibweise des Repository-Namens, also mit großem P)

## Funktionen

- PDFs öffnen, anzeigen und navigieren (Zoom, Seitenbreite, 100-Prozent-Ansicht, Ein- und Doppelseitenansicht, fortlaufender Bildlauf, Tastaturkürzel, Miniaturansichten)
- Ansichtshilfen: Lineale mit Zentimeterinteilung und Gitternetzlinien, ein- und ausblendbar über den Reiter Ansicht; die Lineale liegen fest am Ansichtsbereich, und die Skala beginnt am Blattrand der jeweiligen Seite (oben und links, in der Doppelseitenansicht oben über beide Seiten und zusätzlich rechts), unabhängig von Zoomstufe und Fensterbreite
- Seitenleiste mit vier Ansichten: Seiten, Inhaltsverzeichnis, Lesezeichen und Suchergebnisse; die Ansicht wird über Pfeile links und rechts der mittigen Bezeichnung durchgeschaltet; Leiste vollständig ein- und ausblendbar und in der Breite frei ziehbar
- Seiten löschen, extrahieren, ausschneiden, per Drag-and-Drop umsortieren und drehen; Extrahieren und Ausschneiden wahlweise als PDF-Datei, JPEG oder PNG (Anmerkungen werden mit exportiert, Schwärzungen sind im Bild tatsächlich abgedeckt)
- Textfelder mit Schriftartwahl (Helvetica, Times New Roman, Courier New, Lato, PT Sans, PT Serif, Fira Sans, Ubuntu, IBM Plex Serif, Crimson Text, Space Mono, Arvo) und Schriftgröße als klassisches Dropdown (8 bis 72 Punkt); alle Textformatierungen lassen sich auch vor dem Einfügen als Voreinstellung festlegen; die freien Schriften werden beim Speichern in die Datei eingebettet
- Textformatierung wie in einer Textverarbeitung: Fett, Kursiv, Unterstrichen mit Unterstreichungsarten (einfach, doppelt, gepunktet, gestrichelt, Strichpunkt, wellig), im Menü als Linienmuster dargestellt, Durchgestrichen, Hoch- und Tiefstellen; Piktogramm-Schaltflächen mit Schriftproben, zweizeilig angeordnet
- Farbwahlmenü mit Standardfarben-Kacheln, Optionen „Keine Füllung“ und „Keine Kontur“, und direkt sichtbarer eigener Farbwahl (RGB, HSL und Hex über die Farbauswahl des Browsers), bei Füllungen zusätzlich mit Transparenzregel, bei Konturen mit Strichstärkenwahl
- Textfelder mit Fülleffekt (inklusive Transparenz) und Formkontur; die Größe des Textfelds ändert den Bereich, nicht die Schriftgröße
- LaTeX-Formeln über eine Formel-Schaltfläche (Brüche, Wurzeln, Hoch- und Tiefstellen, griechische Buchstaben, Symbole), beim Speichern als eingebettetes Bild abgelegt
- Pfeile mit einstellbaren Pfeilspitzen: ohne, linke, rechte oder beide Spitzen, offen oder gefüllt
- Strichstärken in Punkten (0,25 bis 6 Pt) und Stricharten: Unilinie, runder Punkt, viereckiger Punkt, gestrichelt, Strichpunktmuster, langer Strich
- Formen und Textfelder drehen: runde Eckgriffe, Seitenbalken zum einseitigen Ziehen, Drehgriff oben, Verschieben in Punkt-Schritten über Richtungspfeile
- Textgebundenes Markieren, Durchstreichen und Unterstreichen direkt am Originaltext; die Farbe wird je Werkzeug über ein Menü am Knopf gewählt, bevor der Text markiert wird
- Lektorieren-Reiter gegliedert in „Standard“ (Auswahlwerkzeug, vorangestellt), „Bestehenden Text bearbeiten“ (Markieren, Durchstreichen, Unterstreichen; Farbe je Werkzeug am Knopf wählbar) und „Ergänzen“ (Text, Formen, Stift, Textmarker)
- Schwärzen als Rechteck oder für markierten Text; mit Sicherheitsmodus wird die Seite beim Speichern als Bild neu aufgebaut, der Inhalt unter der Schwärzung wird dabei tatsächlich entfernt und ist danach nicht mehr markierbar
- Freihändiges Zeichnen mit Stift und Textmarker: beim Aktivieren öffnet sich am Knopf ein Menü mit Deckkraft, Stärke (beziehungsweise Markergröße) und vorausgewählten Farben; der Textmarker kann optional jede Linie nach dem Loslassen automatisch begradigen (waagerecht, senkrecht oder gerade Verbindung)
- Formen einfügen: Rechteck, Ellipse, Dreieck, Raute, Stern, Linie und Pfeil; Formenauswahl, Konturfarbe, Strichstärke, Strichart, Füllung (inklusive Transparenz) und Pfeilspitzen lassen sich im Formformat-Reiter auch vor dem Zeichnen als Voreinstellung festlegen (wird gemerkt); der Reiter öffnet sich beim Aktivieren eines Formwerkzeugs
- Kommentieren: Kommentare an markiertem Text oder an einer Stelle; die Kommentarleiste erscheint automatisch beim ersten Kommentar, ist standardmäßig ausgeblendet und lässt sich über das Kreuz schließen, über die Ansicht wieder öffnen und in der Breite frei ziehen; beim Speichern werden Kommentare als echte PDF-Notizen abgelegt
- Lesezeichen pro Dokument anlegbar (lokal im Browser gespeichert)
- Suche im Dokument: Suchfeld im Start-Reiter; die Trefferliste erscheint in einem eigenen Seitenleisten-Reiter „Suchen” mit Seitenangabe und Textauszug; Weiter- und Zurückspringen über Eingabetaste, F3 und Umschalt+F3; Hervorhebung der Treffer im Seitentext
- Ausfüllbare Formularfelder (AcroForm): Textfelder, Kontrollkästchen, Optionsfelder und Auswahllisten lassen sich direkt im Dokument ausfüllen; die Werte werden beim Speichern fest in die Datei geschrieben
- Reiter Signieren: Signatur als PNG- oder JPEG-Bild einfügen, verschieben und in der Größe ändern; bis zu sechs Signaturen werden im Browser gemerkt und lassen sich per Klick erneut einfügen; beim Speichern wird die Signatur als Bild eingebettet
- Anonymisieren: fremde Kommentare und Markierungen, die bereits in der Datei enthalten sind, je Seite oder dokumentweit entfernen (mit Sicherheitsabfrage; dieser Schritt lässt sich nicht rückgängig machen, Formularfelder und Verknüpfungen bleiben erhalten)
- Komprimieren: alle Seiten werden als JPEG-Bilder neu aufgebaut, wodurch die Dateigröße in der Regel deutlich sinkt; die Größenabweichung wird angezeigt
- Statusleiste unten mit Bibliothekenstatus und Seitenanzeige
- Dateimenü mit Öffnen, Speichern, Speichern unter, Komprimieren, Drucken, Schließen, Optionen (Darstellung Hell oder Dunkel, wird gemerkt) und Lizenz- und Urheberrechtshinweis; in der Ecke liegen nur Rückgängig und Wiederholen
- Rückgängig und Wiederholen für alle Aktionen, mehrfach hintereinander (Strg+Z und Strg+Y sowie Knöpfe)
- Speichern und Speichern unter (freier Dateiname), Drucken der bearbeiteten Datei über den Druckdialog des Browsers

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
| Alpha 0.8 | Korrektur eines Skriptfehlers aus Alpha 0.7 (eine fehlende Klammer blockierte die gesamte Anwendung), zusätzliche eingebettete Schriftarten Lato, PT Sans und PT Serif (mit Fett-, Kursiv- und Fettkursiv-Schnitten, werden beim Speichern in die Datei eingebettet; Fallback auf Helvetica ohne Netzverbindung) |
| Alpha 0.9 | Unterstreichungs- und Durchstreichungslinien haften nun auch bei gedrehten Textfeldern am Text (Kernkorrektur der Drehung), Unterstreichungsarten-Menü im Word-Stil mit Linienmustern und „Ohne“-Eintrag, Schriftgröße als klassisches Dropdown, eigene Farbwahl direkt im Farbwahlmenü (kein Zwischenschritt mehr), Lektorieren-Bereich einheitlich wie das Textfeld-Format gestaltet, Seitenleiste in der Breite ziehbar (150 bis 460 Pixel, wird gemerkt), Selbsttests über den Adresszusatz ?test abrufbar |
| Alpha 0.10 | Korrektur des Darstellungsfehlers beim Zoomen und Drehen (gleichzeitige Darstellungsvorgänge für dieselbe Seite wurden race-artig abgebrochen und hinterließen eine leere oder entstellte Seite; laufende Darstellungen werden nun zuverlässig abgebrochen und neu aufgebaut), Schriftart, Schriftgröße und sämtliche Textformatierungen lassen sich vor dem Einfügen im Textfeld-Reiter als Voreinstellung festlegen (werden gemerkt und auf neue Textfelder angewendet), der Textfeld-Reiter öffnet sich automatisch beim Aktivieren des Textwerkzeugs |
| Alpha 0.11 | Auswahlrahmen und Textdeckung bei Web-Schriftarten korrigiert: die gewählte Schriftart wird beim Wechsel sofort geladen und nach dem Laden werden alle Anmerkungen neu gezeichnet, damit Begrenzungsrahmen und Text immer übereinstimmen (Ursache für Text, der außerhalb seines Rahmens erschien) |
| Alpha 0.12 | Lektorieren-Reiter in „Bestehenden Text bearbeiten“ und „Ergänzen“ gegliedert, Formenauswahl direkt im Formformat-Reiter (das separate Formen-Menü entfällt), Formformat mit Kontur, Strichstärke, Strichart, Füllung und Pfeilspitzen auch vor dem Zeichnen als Voreinstellung festlegbar (wird gemerkt), der Reiter öffnet sich beim Aktivieren eines Formwerkzeugs, Auswahlwerkzeug in der Gruppe „Ergänzen“ |
| Alpha 0.13 | Werkzeugmenüs am Knopf: Stift (Deckkraft, Stärke, Farbe), Textmarker (Deckkraft, Größe, Farbe, Häkchen „Linie begradigen“ — freihändige Striche werden nach dem Loslassen zu geraden Linien ausgerichtet) und Markieren/Durchstreichen/Unterstreichen (Farbe je Werkzeug, vor dem Markieren wählbar), Auswahlwerkzeug vorangestellt in eigener Gruppe „Standard“ (Stift und Textmarker öffnen keinen Formformat-Reiter mehr), sechs zusätzliche freie Schriftarten (Fira Sans, Ubuntu, IBM Plex Serif, Crimson Text, Space Mono, Arvo, mit allen Schnitten eingebettet) |
| Alpha 0.14 | Korrektur des Ladefehlers aus Alpha 0.13 (ein Initialisierungsfehler blockierte die Werkzeugmenüs und damit die gesamte Oberfläche), Rückgängig und Wiederholen mehrfach hintereinander (Strg+Z/Strg+Y, Knöpfe in der Ecke), Dateimenü mit Öffnen, Speichern, Speichern unter, Drucken, Schließen, Optionen (Platzhalter) und Lizenzhinweis, Extrahieren und Ausschneiden wahlweise als PDF, JPEG oder PNG |
| Alpha 0.15 | Suche im Dokument (Suchfeld im Start-Reiter, Trefferliste, Weiter- und Zurückspringen mit F3, Hervorhebung der Treffer), AcroForm-Formularfelder ausfüllen (Werte werden beim Speichern fest in die Datei geschrieben), Komprimieren im Dateimenü (Seiten werden als JPEG-Bilder neu aufgebaut), fremde Kommentare und Markierungen je Seite oder dokumentweit entfernen (mit Sicherheitsabfrage, nicht rückgängig machbar, Formularfelder bleiben erhalten), Reiter Signieren (Signaturbilder als PNG/JPEG, werden im Browser gemerkt und beim Speichern als Bild eingebettet), Darstellung Hell oder Dunkel in den Optionen (wird gemerkt) |
| Alpha 0.16 | Korrektur der Lineale: die Skalen liegen nun fest am Ansichtsbereich und beginnen am Blattrand der jeweiligen Seite (oben und links, in der Doppelseitenansicht oben über beide Seiten und zusätzlich rechts), unabhängig von Zoomstufe und Fensterbreite; Suchtreffer erscheinen in einem eigenen Seitenleisten-Reiter „Suchen”; Korrektur des Optionsfensters (die Hell-/Dunkel-Auswahl ließ sich zuvor nicht öffnen) |
| Alpha 0.17 | Seitenleiste als Auswahlleiste: die Ansichten Seiten, Inhaltsverzeichnis, Lesezeichen und Suchergebnisse werden über Pfeile links und rechts der mittigen Bezeichnung durchgeschaltet; Kommentarleiste in der Breite frei ziehbar (wird gemerkt); Ansichtsbereich bereinigt (die Umschalter für Lesezeichenleiste, Inhaltsverzeichnis und Lesezeichen hinzufügen entfallen, da die Seitenleiste diese Auswahl übernimmt) |

## Hinweise und Grenzen

- Passwortgeschützte PDFs werden nicht unterstützt.
- Eingefügter Text wird in den Schriften Helvetica, Times New Roman, Courier New, Lato, PT Sans, PT Serif, Fira Sans, Ubuntu, IBM Plex Serif, Crimson Text, Space Mono oder Arvo gespeichert (die freien Schriften werden beim Speichern in die Datei eingebettet); der westeuropäische Zeichensatz wird unterstützt.
- LaTeX-Formeln werden beim Speichern als eingebettetes Bild abgelegt, da die PDF-Standardschriften keine mathematischen Symbole enthalten.
- Wellige Unterstreichungen werden beim Speichern als gerade Linie angenähert; gedrehter Text wird beim Speichern an gleicher Stelle ohne Drehung abgelegt.
- Schwärzungen ohne Sicherheitsmodus verdecken den Inhalt nur optisch; der Text bleibt in der Datei enthalten. Der Sicherheitsmodus ist daher standardmäßig aktiviert. Beim Bild-Export (JPEG/PNG) sind geschwärzte Bereiche im Bild abgedeckt.
- Beim Export mehrerer Seiten als JPEG oder PNG lädt der Browser mehrere Dateien nacheinander herunter und fragt gegebenenfalls nach Erlaubnis.
- Ausgefüllte Formularfelder werden beim Speichern fest in die Datei geschrieben (eingebrannt); die Felder sind danach nicht mehr änderbar.
- Signaturen werden als Bild in die Datei eingebettet. Das Entfernen fremder Kommentare und Markierungen greift direkt in die Datei ein und lässt sich nicht rückgängig machen.
- Die Komprimierung baut alle Seiten als JPEG-Bilder neu auf; dabei verliert der Text seine Markierbarkeit (er ist dann Teil des Bildes), und feine Grafiken können etwas an Schärfe verlieren.

## Lizenz

Dieses Projekt steht unter der [GNU Affero General Public License 3.0](LICENSE). Beim Betrieb als Web-Dienst muss der Quellcode den Nutzerinnen und Nutzern zugänglich gemacht werden.
