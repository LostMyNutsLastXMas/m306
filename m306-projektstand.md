# M306 Abschlussprojekt – Projektstand

Stand: 12.10.2026, Termine nachgeführt am 25.10.2026 (Abgabe So 25.10.2026, Präsentation nach der Abgabe; Word-Dokument massgebend im TBZ-OneDrive) · Diese Datei liegt im Git-Repository (Projektordner) und im Claude-Projekt (claude/m306-projektstand.md).

> **Für KI-Assistenten:** Lies zuerst die Abschnitte «Offene Punkte für Nicolas» und «Regeln für die Zusammenarbeit». Die übrigen Abschnitte sind Hintergrund und Arbeitsprotokoll. Massgebend sind das Word-Dokument `M306_9_Abschlussprojekt_Hunger_Weisshaar.docx` und die Bewertungstabelle `tests/bewertung/Bewertung_K1-K10.xlsx`.

## Stand 25.10.2026

Abgegeben: `M306_9_Abschlussprojekt_Hunger_Weisshaar.pdf` (Dokumentation inkl. Anhang A) und `M306_9_Praesentation_Hunger_Weisshaar.pdf` (Folien, Präsentation am Mi 28.10.2026). Bewertung Nicolas, Test der Anleitung (25.10., 7 Min.), Reflexion Nicolas und Ist-Aufwand sind eingetragen; Pflichtenheft auf Anweisung der Lehrperson entfernt; Checkliste «Dokumentenbewertung» entfernt. Die Word-Datei im Repo ist die Endfassung (ohne Überarbeitungen).

## Offene Punkte für Nicolas (Stand 12.10.2026)

Erledigte Punkte mit [x] abhaken und die Datei committen und pushen.

### 1. Bewertung K1–K10 – bis spätestens Mi 14.10. (M3 Tool-Entscheid)

- [x] Blatt «K1–K4 pro Prompt»: gelbe Spalten «Nicolas» ausfüllen, D = K1 Bildqualität, G = K2 Prompt-Treue, J = K3 Text im Bild, M = K4 Stilvielfalt, jeweils Zeilen 5–22 (Gemini P1–P6 = Zeilen 5–10, ChatGPT P1–P6 = 11–16, Leonardo.Ai P1–P6 = 17–22), total 72 Werte
- [x] Blatt «Nutzwert»: K5–K10 in den gelben Zellen E9:E14 (Gemini), H9:H14 (ChatGPT) und K9:K14 (Leonardo.Ai), total 18 Werte. K1–K4 berechnet die Tabelle selbst aus dem ersten Blatt.
- [ ] Rot markierte Abweichungen (2 oder mehr Punkte Unterschied zu Lucas) gemeinsam mit Lucas anschauen und neu bewerten (Risiko R3) → 25.10.: nicht gemeinsam neu bewertet (Zeit), Mittelwerte bleiben; in Evaluation und Risiko-Überprüfung vermerkt.
- [x] Excel committen und pushen, Lucas Bescheid geben. Lucas trägt danach die Mittelwerte im Word nach (Nutzwertanalyse, Evaluation, Anhang B Spalte «Nicolas», Zusammenfassung).

Hinweise:
- Ganze Punkte 1–5 nach der Skala (Blatt «Skala» im Excel und Tabelle «Bewertungsskala» im Word, Kapitel Lastenheft).
- Unabhängig bewerten: eigene Einschätzung, die Werte von Lucas nicht übernehmen. Genau dafür ist die zweite Bewertung da (R3, «es zählt der Mittelwert»).
- Grundlagen: Ergebnisbilder in `tests/gemini`, `tests/chatgpt`, `tests/leonardo` (pN.*; Folge-Prompt für K5: folge-p1.*, bei Leonardo.Ai zählt der zweite Versuch mit Referenzbild, siehe Anhang B); Nachweise für K6 und K9 in `tests/muss/<tool>/`; Prompts P1–P6 im Word (Lastenheft, Tabelle «Test-Prompts»); Fakten zu K7 und K9 im Word (Nutzwertanalyse, Begründungen) und unten unter «Recherche».

### 2. Test der Anleitung mit Testperson – bis Sa 17.10. (M4, Paket 5.1, Ziel 4)

- [x] Testperson ausserhalb des Teams finden, die zur Zielgruppe gehört (gelegentliche Nutzung, idealerweise noch ohne ChatGPT-Konto). Einverständnis einholen, dass Name, Alter und Beruf in der Dokumentation stehen.
- [x] Test durchführen: Die Testperson arbeitet nur mit der Kurzanleitung «Bilder erstellen mit ChatGPT» (Word, Kapitel Realisierung, Abschnitt 1). Aufgabe: «Ein Bild für die Einladung zu einem Grillfest im Team erstellen und speichern». Nicht helfen. Zeit vom Öffnen von chatgpt.com bis zum gespeicherten Bild messen (Ziel: höchstens 15 Minuten).
- [x] Festhalten: Name, Alter, Beruf, vorher Konto bei ChatGPT (ja/nein), Datum, Zeit in Minuten, Ergebnis (erfüllt / nicht erfüllt), Probleme, Rückmeldung, Anpassungen an der Anleitung. Ergebnisbild ablegen, z.B. in `tests/testperson/`.
- [x] Eintragen im Word (oder Ergebnisse an Lucas schicken):
  - Realisierung, Abschnitt 2 «Test der Anleitung»: gelbe Platzhalter in der Tabelle ersetzen
  - Kapitel Organigramm, Tabelle «Rollen und Aufgaben», Zeile «Fachvertreter»: «Testperson aus der Zielgruppe (noch offen)» ersetzen
  - Zusammenfassung: Abschnitt 1 «Ergebnisse» (Punkt «Anleitung») und Abschnitt 2 «Zielerreichung» (Ziel 4)
- [x] Anleitung korrigieren, falls die Testperson irgendwo nicht weiterkam (Lieferobjekt von 5.1: «Testprotokoll, korrigierte Anleitung»)

### 3. Reflexion – bis spätestens Mi 21.10. (Paket 7.2)

- [x] Word, Kapitel «Reflexion (individuell je Teammitglied)»: gelben Platzhalter unter «Nicolas Hunger» ersetzen
- [x] Aufbau wie bei Lucas: drei Absätze in Ich-Form mit fetten Einstiegen «Was lief gut?», «Was würde ich anders machen?» und «Gelerntes / Nächste Entwicklungsschritte:», insgesamt ca. 150–250 Wörter. Eigene Erfahrungen (Vorgabe: «Eigene Erkenntnisse und Reflexion jedes Teammitglieds»).

### 4. Präsentation – Mi 21.10. (Pakete 6.1 und 6.2, gemeinsam mit Lucas)

- [x] Folien zusammen mit Lucas erstellen, Aufteilung absprechen
- [x] Checkliste «Dokumentenbewertung», Abschnitt «Präsentation und Demonstration», beachten: Präsentationsfolien, Live-Demo mit Prompt-Cases, User-Dokumentation (= Kurzanleitung)
- Live-Demo: Prompts P1, P3, P5 und ein Folge-Prompt (Word, Realisierung, Abschnitt 3). Den Probelauf macht Lucas (Paket 5.2).

### 5. Tatsächlicher Aufwand – vor der Abgabe

- [x] Eigene Stunden für das ganze Projekt schätzen und Lucas melden. Sie kommen in die Zusammenfassung, Abschnitt 3 «Vergleich geplant/tatsächlich» (geplant für Nicolas: 15,75 h).

### 6. Mit Lucas klären

- [ ] Aufwandverteilung: Paket 4.1 «Tool einrichten, Anleitung schreiben» (3 h) steht im Plan bei Nicolas, die Kurzanleitung hat aber Lucas geschrieben. Der Plan zeigt Lucas ca. 24,25 h und Nicolas ca. 15,75 h, im Teamkapitel steht als Teamziel «je ca. 20 Stunden». Entscheiden, ob Nicolas andere Pakete übernimmt (z.B. 6.1 Präsentation). Planänderungen immer in der Excel-Planung UND im Gantt-Plan im Word nachführen. → offen; Ist-Aufwand Lucas ca. 13 h, Nicolas ca. 10 h in der Zusammenfassung.
- [x] Risiko-Überprüfung bei M3 (14.10.) und M4 (17.10.): Stand der eigenen Risiken R1, R2 und R6 melden (Nicolas ist dort Risiko-Verantwortlicher)

## Regeln für die Zusammenarbeit

- **Git:** Word- und Excel-Dateien sind binär und lassen sich nicht zusammenführen. Vor dem Bearbeiten `git pull`, die Bearbeitung im Team kurz ankündigen, danach sofort committen und pushen. Nie gleichzeitig dieselbe Datei bearbeiten.
- **Sprache:** Schweizer Rechtschreibung (ss statt ß), sachlich, keine Emojis. Kein Hinweis auf KI-Unterstützung in der Dokumentation (Entscheid des Teams).
- **Platzhalter:** stehen in [eckigen Klammern] und sind gelb markiert. Beim Ausfüllen Klammern und Markierung entfernen.
- **Namen:** Reihenfolge überall «Hunger, Weisshaar».
- **Formatierung, Quellen, Abkürzungen:** siehe Abschnitt «Arbeitsweise».

## Rahmendaten
- Projekt: Evaluation & Einführung eines KI-Bildgenerators (Free-Tier), Vorgehen nach Wasserfallmodell
- Team: Nicolas Hunger, Lucas Weisshaar (Projektleiter) – Namensreihenfolge überall «Hunger, Weisshaar» (Ausnahme: Organigramm-Grafik, dort PL zuerst)
- Auftraggeber: Herr Bisig (TBZ) – muss nichts genehmigen; der Projektantrag dient nur dem Realismus
- Laufzeit: 23.09.2026 – 21.10.2026 (KW 39–43); Abgabe als ein PDF: M306_9_Abschlussprojekt_Hunger_Weisshaar.pdf
- Zeitplan ist nicht strikt; das Team arbeitet viel mit KI und flexibel
- Herbstferien Berufsfachschulen Kanton Zürich: 05.–17.10.2026 (KW 41–42)
- Entscheide: nur Bilder (keine Videos), nur Free-Tier; Tools: Google Gemini (Nano Banana 2), ChatGPT-Bildgenerierung, Leonardo.Ai
- Zielgruppe: Personen, die gelegentlich ein Bild brauchen (festlicher Anlass, Arbeit, humorvoller Anlass); Persona im Lastenheft: «Sandra, 34, kaufmännische Angestellte»
- Testperson (Fachvertreter, prüft die Anleitung): noch offen (dringend, nötig für M4); in der Realisierung und im Organigramm (Rollen-Tabelle «noch offen») vorerst Platzhalter
- Team-Organisation: Kommunikation über WhatsApp und Discord; Ablage im GitHub-Repository «m306», der Projektordner ist die Arbeitskopie (Stand 12.10.2026) – die 6 GitHub-Stellen im Dokument (Teamkapitel 3×, Lastenheft, Nutzwertanalyse, Pflichtenheft) stimmen damit; im Teamkapitel steht noch «Bis es eingerichtet ist, speichern wir lokal.» (kann bleiben); wöchentlicher Abgleich mittwochs (Ferien: Discord-Call); kein Board; KEIN Hinweis auf KI-Unterstützung in der Dokumentation (Entscheid des Teams, nicht erneut vorschlagen)

## Dateien (Projektordner = Git-Repository)
- m306-projektstand.md – dieser Projektstand (auch im Claude-Projekt unter claude/m306-projektstand.md)
- Projekt-Dokumentation-Vorlage.docx – Original, bleibt unverändert
- M306_9_Abschlussprojekt_Hunger_Weisshaar.docx – massgebende Arbeitskopie (seit 12.10.2026 nachmittags so benannt; vorher «… 9 2.docx» aus OneDrive). Von Word neu gespeichert: deutsche Formatvorlagen-IDs (berschrift1–3, Standard, Titel, Verzeichnis1–3, Inhaltsverzeichnisberschrift), Tabellenformatvorlagen a/a0/a1/a3 tragen den Zellabstand (0 nach, einfacher Zeilenabstand), eingebettete Schriften (ca. 5,9 MB). LibreOffice zeigt Tabellen mit mehr Abstand (38 Seiten) → Seitenzahlen im Inhaltsverzeichnis nicht mit LibreOffice berechnen, sondern in Word aktualisieren. Bilder: image1.png (Abb. 1 Organigramm), image4.jpeg (Abb. 2 Vergleich P4), image5–8.png (Abb. 3–6 Anleitung: Registrierung, Datenkontrollen, Bild erzeugen, Anpassen/Speichern), image3.png (Abb. B1 Limit-Meldung), image2.jpeg (Abb. B2 Bildübersicht); docPr-IDs 1–8 vergeben, nächste Bild-rId: rId20
- Gemeinsame Ablage: GitHub-Repository (Stand 12.10.2026; vorher OneDrive (TBZ)). Nach jeder Änderung committen und pushen (gleiche Dateinamen); vor Änderungen `git pull` und klären, wer gerade an welcher Datei arbeitet
- Vorlage_Projektplanung_M306.xlsx – Original der Planungsvorlage, bleibt unverändert
- M306_Projektplanung_Hunger_Weisshaar.xlsx – ausgefüllte Planungsvorlage (KW39–43, Formeln Total/Lucas/Nicolas, Druck A4 quer, 2 Seiten, Druckbereich A1:L37 inkl. Änderungsnotiz in B37). Mit LibreOffice gespeichert; Änderungen direkt im XML, zwischengespeicherte Formelwerte (F30–F32) von Hand nachführen. Keine Ist-Spalte (Entscheid 12.10.: Ist-Aufwand nur in der Zusammenfassung)
- Skript-ohne-Inhaltsverzeichnis.pdf – Theorie-Skript M306 (V3.1.5)
- Claude outputs/Organigramm_Entwurf.png – Organigramm als Bild (von der App abgelegt)
- tests/gemini, tests/chatgpt, tests/leonardo: Ergebnisbilder pN.jpeg/png/jpg, Screenshots «pN-2026-10-12- hh.mm.ss.png», folge-p1.*; chatgpt/reach-of-limit-1.png (Meldung: Kontingent wird um 1:00 zurückgesetzt); chatgpt/p5, p6 (12.10.2026, 15:21/15:24, zweites Gratis-Konto); leonardo/«Screenshot 2026-10-12 at 02.15.14.png» (Folge-Prompt, 2. Versuch, Modell Nano Banana, Token 54); gemini/how-many-pictures-can-be-taken-in-free-tier.png (KI-Übersicht der Google-Suche, stützt sich auf YouTube/Reddit → nicht als Quelle verwenden). Screenshots zeigen Kontonamen und Standort → in der Doku nur zugeschnitten verwenden
- tests/realisieren/registration.png und options.png (12.10.2026, Inkognito-Fenster): Startseite mit «Kostenlos registrieren», Fenster «Anmelden oder registrieren» (Google, Apple, Telefonnummer, E-Mail)
- tests/muss/<tool>/: Screenshots Muss-Prüfung K6/K9 (Gemini 6, ChatGPT 6, Leonardo.Ai 12; 11./12.10.2026)
- tests/bewertung/Bewertung_K1-K10.xlsx (12.10.2026): Blätter Anleitung, «K1–K4 pro Prompt» (Lucas blau, Nicolas gelb leer, Ø, Abweichung ≥ 2 rot), Nutzwert (K1–K10, Gewichtung, Ø, Nutzwert, Muss, Rang), Skala. Nicolas trägt in dieselbe Datei ein (Stand 12.10.2026: Spalten «Nicolas» noch leer)
- Testplan (Claude Doc, 11.10.2026): https://claude.ai/code/artifact/196f75bb-1ce3-4ac6-b6e6-6a4d4986692a

## Arbeitsweise
- Abschnittsweise: Checkliste aus Vorlage + Skript → Entwurf im Chat → gemeinsame Prüfung → erst nach OK ins Word-Dokument
- Jedes Thema mit Zweck, Theorie mit Quellen und Praxis (Checkliste «Dokumentenbewertung»)
- Blaue Hinweistexte beim Ausfüllen eines Abschnitts löschen; schwarze Vorgabe-Stichworte der Vorlage durch eigene Inhalte entlang derselben Stichworte ersetzen
- Quellen- und Abkürzungsverzeichnis laufend nachführen (Format: Autor (Jahr): Titel. Verlag/URL (Zugriff am dd.mm.yyyy).); Kurzverweise im Text, z.B. (Skript M306, Kap. 5.3.1) oder (Lewis et al. 2024)
- Schweizer Rechtschreibung (ss statt ß); Aufzählungen im Stil der Vorlage («• » mit Zeilenumbruch, fette Stichworte vorne); Zwischentitel fett (nummeriert 1., 2., 3.1 …); Kapitel als Überschrift 1, Unterkapitel als Überschrift 3 (erscheinen im Inhaltsverzeichnis; Zusammenfassung/Reflexion und Dokumentenbewertung bleiben wie in der Vorlage Überschrift 2); Abbildungen mit Bildunterschrift «Abbildung n: …» (im Anhang eigene Nummerierung B1, B2 …)
- Platzhalter für fehlende Angaben in eckigen Klammern und gelb markiert (z.B. Test der Anleitung)
- Eigene Tabellen: Kopfzeile fett mit hellblauer Füllung (DCE6F2), 10 pt, Zeilen nicht über Seiten trennen, Kopfzeile wiederholen, Breite = Satzspiegel (9071 twips), Zellrand 57 twips; Summenzeilen grau (F2F2F2); Absatz direkt nach einer Tabelle mit Abstand vor 120
- Versionierung: 0.1 = Arbeitsstand, 1.0 = Abgabe; Datum auf Titelblatt und in Fusszeile bei jeder Bearbeitung nachführen (auch Fusszeile der Excel-Planung)
- Kopfzeile: «M306 – Evaluation KI‑Bildgenerator | Hunger, Weisshaar»; Fusszeile: «Version 0.1 | Datum» links, «Seite X von Y» rechts
- Planänderungen immer in Excel UND in der Gantt-Tabelle im Word nachführen; Abweichungen im Word unter der Gantt-Tabelle als Zwischentitel «Stand dd.mm.yyyy» festhalten, Risiko-Überprüfungen unter dem Register als «Überprüfung am dd.mm.yyyy»
- Reflexion: Lucas/Nicolas liefern Stichsätze, Claude formuliert sie als Fliesstext in Ich-Form aus, ohne eigene Erfahrungen zu ergänzen (kleine Ergänzungen nur markiert und mit OK)
- Formatvorlagen: keine Formatvorlagen mit gleichem Namen doppelt anlegen, vorhandene anpassen; seit dem Word-Speichern deutsche IDs verwenden (siehe Dateien)

## Status
- Erledigt: Titelblatt, Inhaltsverzeichnis, Einleitung, Kopf-/Fusszeile, Sprache de-CH, A4, Ziele (SMART), Projektantrag, Vorgehens-Management, Organigramm, Projektplanung (Gantt + Excel, nachgeführt 12.10.2026), Projektrisiken (Register R1–R7, Matrix, Überprüfung 12.10.2026 mit R1 und R5), Team/Teambildung/Führung, Lastenheft, Nutzwertanalyse (vorläufige Werte Lucas), Test-Prompts, Pflichtenheft, Evaluation (vorläufig, 12.10.2026), Realisierung (Kurzanleitung 12.10.2026; Test und Probelauf noch offen), Zusammenfassung (12.10.2026; gelbe Platzhalter offen), Reflexion Lucas (12.10.2026), Quellenverzeichnis (11 Quellen), Abkürzungsverzeichnis (22 Einträge), Anhang A (Hinweis Excel-Plan), Anhang B «Testprotokoll» (12.10.2026)
- Noch offen in der Doku: Realisierung Abschnitt 2 (Test der Anleitung, gelbe Platzhalter) und Probelauf-Datum in Abschnitt 3; Platzhalter der Zusammenfassung (Nutzwerte nach Nicolas, Test der Anleitung, Live-Demo, Daten M3–M5, Ist-Aufwand Lucas/Nicolas/total, Abweichung in %, Erreicht-Spalte Ziele 3–6 und 8); Reflexion Nicolas (gelber Platzhalter); Block «Formelle Vorgaben & Abgabehinweise» aus der Vorlage (vor Abgabe entfernen), Checkliste «Dokumentenbewertung» abhaken (blaue Vorlage-Punkte bei «Präsentation und Demonstration»: Präsentationsfolien, Demo, User-Dokumentation)
- Inhaltsverzeichnis: Standard-Word-Feld «TOC \o "1-3" \h \z \u» mit Links; Seitenzahlen vor Abgabe in Word aktualisieren. Anhang A und B seit 12.10. als Überschrift 3 → erscheinen erst nach «Gesamtes Verzeichnis aktualisieren» in Word
- Lastenheft, Nutzwertanalyse, Pflichtenheft, Test-Prompts: siehe frühere Einträge (Kriterien K1–K10 mit Gewichtung 20/15/10/10/5/10 Muss/5/10/10 Muss/5 %; Skala 1–5 mit Ankern 5/3/1; Testvorgehen; Prompts P1–P6 + ein Folge-Prompt auf P1). Pflichtenheft 3.3: A1–A3 MUSS (Tool), A4 Anleitung ≤ 15 Min. (MUSS, Testperson), A5 Live-Demo (MUSS), A6–A8 WUNSCH
- Tests: 12.10.2026, ca. 00:49–02:15: Gemini P1–P6 + Folge; ChatGPT P1–P4 + Folge (danach Tageslimit, «max. 5 Bilder»); Leonardo.Ai P1–P6 + Folge (Model Auto, Style Dynamic, 1:1, 1024×1024, 1 Bild). ChatGPT P5/P6 am 12.10.2026, 15:21/15:24 mit einem zweiten Gratis-Konto von Lucas nachgeholt (Massnahme R1). Alle Tests abgeschlossen; getestet hat Lucas (Pflichtenheft 3.1, Ziel 2 und RACI-Matrix nennen Nicolas → bleiben als ursprünglicher Plan; Abweichung in Anhang B «Rollen», in der Projektplanung «Stand 12.10.2026» und in der Zusammenfassung; Gantt/Excel 3.1 seit 12.10. auf Lucas). Wartezeit nicht gestoppt (in Anhang B, Evaluation und Zusammenfassung als nicht geprüft vermerkt)
- Leonardo.Ai Folge-Prompt: 1. Versuch (nach P1) ohne Referenzbild ergab ein neues Bild (Heissluftballon); 2. Versuch (02:15) mit P1 als Referenz, Leonardo.Ai wählte automatisch «Nano Banana» (40 Tokens). Entscheid 12.10.: K5 = 4 bleibt (2. Versuch = richtige Bedienung, Fehlversuch zeigt sich bei K8)
- Leonardo.Ai Tokens laut Screenshots: 8 pro Bild im Auto-Modus (142 nach P1, 126 nach P2 inkl. Heissluftballon, 94 nach P6, 54 nach Folge) → ca. 18 Bilder pro Tag; K7 = 4; Begründung K7 in Word und Excel «8 pro Bild (ca. 18 Bilder)»
- K5–K10 (Lucas, im Word mit einer Nachkommastelle): K5 5/5/4 · K6 5/5/5 · K7 5/3/4 · K8 5/5/3 · K9 5/5/2 · K10 5/5/4 (Reihenfolge Gemini/ChatGPT/Leonardo.Ai)
- K1–K4 (Vorschlag als Bewertung Lucas, 12.10.2026; pro Prompt mit Begründung im Excel und in Anhang B): Gemini K1 4,8 · K2 4,0 · K3 5,0 · K4 4,8 · ChatGPT (P1–P6) K1 5,0 · K2 5,0 · K3 5,0 · K4 4,8 · Leonardo.Ai K1 4,8 · K2 5,0 · K3 5,0 · K4 4,8
- Korrektur 12.10.: Leonardo.Ai P6 K3 von 3 auf 5 – «Zurück» in Schreibschrift ist korrekt (ein «ü» sieht in Schreibschrift fast gleich aus wie «ii»; ChatGPT P6 zeigt dieselbe Form)
- Nutzwert vorläufig (nur Lucas): ChatGPT 4,88 · Gemini 4,79 · Leonardo.Ai 4,29; Muss bei allen erfüllt; Rang 1 ChatGPT, 2 Gemini, 3 Leonardo.Ai. Im Word und Excel identisch; Hinweis im Word «Vorläufig: Bewertung Nicolas folgt.»; in der Zusammenfassung als gelbe Platzhalter [4,88]/[4,79]/[4,29]
- Evaluation (Word, 12.10.2026, vorläufig): Einleitung mit Skript M306 Kap. 4.7.1–4.7.2; 1. Ergebnis der Nutzwertanalyse (Tabelle); 2. Entscheidungsfolgen (Matrix Qualität/Termin/Kosten/Personal × ChatGPT/Gemini/Leonardo.Ai/kein Entscheid bis 14.10.); 3. Empfehlung ChatGPT mit Abbildung 2 (P4 Gemini vs. ChatGPT); 4. Erfüllung MUSS A1–A3 (Tabelle); 5. Grenzen und nächste Schritte (vorläufig, knapper Abstand: K7 auf 10 % zulasten K5 → Gemini +0,01, Momentaufnahme, Wartezeit nicht gemessen). Nach Nicolas' Bewertung Zahlen und ggf. Empfehlung nachführen
- Realisierung (Word, 12.10.2026): Einleitung mit Skript M306 Kap. 5.3; 1. Kurzanleitung «Bilder erstellen mit ChatGPT» (Stand Oktober 2026, Webbrowser, keine Installation, A8 Smartphone weggelassen – Entscheid Lucas; Ansprache «du»): Schritt 1 Konto einrichten (Kostenlos registrieren → E-Mail → Bestätigungscode → Name und Alter; Mindestalter 13, unter 18 mit Zustimmung der Eltern, OpenAI o. J.) mit Abb. 3; Schritt 2 Datenschutz einstellen (Einstellungen → Datenkontrollen → «Das Modell für alle verbessern» aus) mit Abb. 4; Schritt 3 Bild erzeugen (Prompt-Formel Motiv, Anlass, Stil, Text) mit Abb. 5; Schritt 4 Bild anpassen (Folge-Prompt mit «nur … alles andere gleich»); Schritt 5 Bild speichern (Download-Symbol, PNG) mit Abb. 6; Gut zu wissen (Tageslimit mit Verweis auf Abb. B1, Gemini als Ausweichmöglichkeit, Rechte, Datenschutz, Texte prüfen); Prompt-Beispiele P1/P3/P5 (A7); 2. Test der Anleitung (A4, Ziel 4) als Tabelle mit gelben Platzhaltern, Testaufgabe «Einladung zu einem Grillfest im Team» (bewusst kein Beispiel aus der Anleitung); 3. Vorbereitung Live-Demo (A5): Prompts P1/P3/P5 + Folge-Prompt = 4 Bilder, Plan B (R7), Probelauf-Datum offen
- Zusammenfassung (Word, 12.10.2026, Entwurf von Lucas freigegeben): Einleitung mit Skript M306 Kap. 5.3 (Projektabschluss: Übergabe, Schulung, Nachkalkulation, Lessons learned) und Kap. 2.1–2.2 (Erfahrungswerte, Schätzungsabweichung i.d.R. ±50 %); 1. Ergebnisse (Vergleich 21 Tests, Entscheid ChatGPT mit Nutzwerten als Platzhalter und K2 als Ausschlag, Anleitung, Live-Demo, Kosten 0 CHF); 2. Zielerreichung (Tabelle # / Ziel / Ergebnis / Erreicht: Ziele 1, 2, 7 erfüllt; 3–6 und 8 mit Platzhaltern); 3. Vergleich geplant/tatsächlich (Tabelle Punkt / Geplant / Tatsächlich: M0–M2 termingerecht, M3–M5 [TT.MM.], Aufwand Lucas 24,25 h, Nicolas 15,75 h, total 40 h nach Gantt-Stand 12.10. (ursprünglich je ca. 20 h), Ist [__ h], Kosten 0 CHF; Abweichung [__ %]; Abweichungen vom Plan: Tests KW 42 und Lucas statt Nicolas, R1 mit zweitem Konto, Wartezeit und A8 nicht umgesetzt); 4. Erkenntnisse (Limiten früh klären, Bewertung vorbereiten, Ergebnis mit Datum). Sätze zu K2 und Nutzwerten nach Nicolas' Bewertung prüfen; Aufwandzahlen anpassen, falls Paket 4.1 umgeteilt wird
- Reflexion (Word, 12.10.2026, Entwurf von Lucas freigegeben): Einleitung mit Skript M306 Kap. 5.3 (Debriefing/Lessons learned); Zwischentitel «Nicolas Hunger» (gelber Platzhalter) und «Lucas Weisshaar» (Reihenfolge Hunger, Weisshaar); Lucas in Ich-Form mit fetten Einstiegen «Was lief gut?» (Zusammenarbeit, gutes Ergebnis, Tools testen machte Spass), «Was würde ich anders machen?» (im Projekt nichts; Kritik: M306, M426 und M431 überschneiden sich, könnten zu einem Modul zusammengefasst werden – sachlich formuliert), «Gelerntes / Nächste Entwicklungsschritte:» (als Projektleiter Verantwortung übernehmen, auch künftig vorstellbar; Projektstruktur «von den Zielen über die Planung bis zum Abschluss» – Ergänzung von Lucas genehmigt)
- Entscheid 12.10. (Lucas): M1 (02.10.) und M2 (07.10.) termingerecht erreicht; Ist-Aufwand nur in der Zusammenfassung (keine Ist-Spalte im Plan), Stunden am Schluss schätzen
- Entscheid 12.10.: Claude bewertet K1–K4 als Vorschlag, Lucas prüft ihn als seine Bewertung, Nicolas bewertet unabhängig (gelbe Zellen im Excel), danach Mittelwerte ins Word (Vorgehen R3 bleibt so in der Doku)
- Entscheid 12.10. (nachmittags): Nicolas trägt in dieselbe Excel-Datei ein, keine separate Datei (nicht erneut vorschlagen)
- Anhang B (Word, 12.10.2026): Einleitung mit Skript-Verweisen (Kap. 5.3 Protokolle, Kap. 7.3.1 Prüfplan); 1. Testumgebung und Ablauf; 2. Abweichungen (ChatGPT-Limit + zweites Konto, Leonardo Folge-Prompt, Wartezeit nicht gestoppt, Rollen: Lucas statt Nicolas) mit Abbildung B1 (Limit-Meldung, zugeschnitten); 3.–5. Protokolltabellen pro Tool (T01–T21 + Zeile K5–K10, Spalte Nicolas leer → nach seiner Bewertung füllen); 6. Nachweise Muss-Prüfung; 7. Bildübersicht = Abbildung B2
- Projektplanung nachgeführt (Word + Excel, 12.10.2026, Wunsch Lucas): Paket 3.1 «Konten einrichten, Vergleichstests» bei Lucas statt Nicolas, nur KW 42 (vorher KW 41–42); geschätzter Aufwand neu Lucas ca. 24,25 h, Nicolas ca. 15,75 h (vorher 20,25/19,75; total 40 h). Word: Zwischentitel «Stand 12.10.2026» unter dem Hinweis auf Anhang A (Verschiebung und Rollentausch 3.1; R1 mit zweitem Konto gelöst, Termin Ziel 2 (13.10.) nicht gefährdet). Excel: G12 Lucas, J12 (KW 41) leer, Summen F31/F32, Änderungsnotiz in B37, Fusszeile «Version 0.1 | 12.10.2026». Offen: Paket 4.1 (siehe «Offene Punkte für Nicolas», Punkt 6)
- Meilensteine: M0 Mi 23.09. Start · M1 Fr 02.10. Projektantrag erstellt · M2 Mi 07.10. Kriterien + Test-Prompts · M3 Mi 14.10. Tool-Entscheid · M4 Sa 17.10. Anleitung + Demo getestet · M5 Mi 21.10. Abgabe + Präsentation (M0–M2 termingerecht erreicht)
- Risiken (P×I): R1 Tageslimiten 12 (eingetreten bei ChatGPT, mit zweitem Konto gelöst) · R2 Anbieteränderung 9 · R3 subjektive Bewertung 12 · R4 Zeit 15 (hoch) · R5 Ausfall 8 (kurz eingetreten: zu Beginn fiel ein Teammitglied wegen Krankheit kurz aus, M1/M2 trotzdem termingerecht; Entscheid Lucas 12.10.) · R6 Nutzungsbedingungen 4 · R7 Live-Demo 12. Risiko-Verantwortliche: Nicolas R1, R2, R6; Lucas R3, R4, R5, R7. Im Word Zwischentitel «Überprüfung am 12.10.2026» nach dem Satz zu R4 mit den Punkten «R1 eingetreten», «R5 kurz eingetreten», «Übrige Risiken» (bleiben wie bewertet, R3 nach Bewertung Nicolas prüfen). Laut Doku Überprüfung bei jedem Meilenstein (M3, M4 noch offen)
- Abkürzungsverzeichnis (12.10.2026): 22 Einträge, neu JPEG, M426 «Software mit agilen Methoden entwickeln», M431 «Aufträge im eigenen Berufsumfeld selbständig durchführen», PNG (M306 weiterhin mit Skript-Titel «IT-Kleinprojekte abwickeln»)
- Nächste Schritte Lucas: Word und diese Datei committen und pushen; nach Nicolas' Bewertung die Mittelwerte und definitiven Nutzwerte in NWA, Anhang B (Spalte Nicolas), Evaluation und Zusammenfassung nachführen, «Vorläufig» entfernen; Probelauf der Live-Demo (Paket 5.2, Datum in Realisierung Abschnitt 3); Präsentationsfolien mit Nicolas; Aufwandverteilung mit Nicolas klären; Risiko-Überprüfung M3 und M4; restliche Platzhalter der Zusammenfassung (Daten M3–M5, Ist-Stunden, Abweichung in %, Live-Demo). Aufgaben von Nicolas: siehe «Offene Punkte für Nicolas»
- Vor Abgabe: gelbe Platzhalter und Vorlage-Hinweise entfernen; Dokumentenbewertung abhaken; Inhaltsverzeichnis in Word aktualisieren; Testperson nachtragen; Version 1.0 + Datum; Excel-Plan (A4 quer) als PDF an das Abgabe-PDF anhängen (Anhang A); alles als ein PDF

## Quellen im Dokument
- Belbin (o. J.), Google (o. J.) Gemini-Limits (Zugriff 12.10.2026), Kanton Zürich (o. J.), Leonardo.Ai (o. J.) Pricing, Lewis et al. (2024), Lexware (2026), microTOOL (2026), OpenAI (o. J.) Nutzungsbedingungen (https://openai.com/policies/eu-terms-of-use/, Zugriff 11.10.2026; zitiert in Evaluation und Realisierung), Rengel et al. (2025) «Skript M306», Rübel (2026), Schwaber & Sutherland (2020). Achtung: weitere Quellen vom selben Autor im selben Jahr brauchen a/b-Zusatz (z.B. Leonardo.Ai o. J. a/b)

## Recherche
- Gemini: Nano Banana 2 auch für Gratis-Nutzer; ab 13 Jahren
- Gemini-Limits (support.google.com/gemini/answer/16275805, Abruf 12.10.2026): nennt für Gratis-Nutzer keine Bildzahl, nur «Standardlimits»; Limit wird alle 5 Stunden aktualisiert, bis das Wochenlimit erreicht ist. KI-Übersicht der Google-Suche (Screenshot von Lucas) nennt «häufig bis rund 30–100 Bilder pro Tag» – nur Sekundärquellen, nicht zitieren
- ChatGPT Free: im Test nach 5 Bildern Limit erreicht, Zurücksetzen laut Meldung um 1:00; Bilder gehören den Nutzenden (OpenAI-Nutzungsbedingungen), Training in den Einstellungen abschaltbar (Screenshot tests/muss/chatgpt); Mindestalter 13, unter 18 mit Zustimmung der Eltern (Nutzungsbedingungen, Abschnitt «Registrierung und Zugang»); Registrierung mit Google, Apple, Telefonnummer oder E-Mail (E-Mail → Bestätigungscode → Name und Alter)
- Leonardo.Ai Free: 150 Tokens pro Tag, im Test 8 Tokens pro Bild im Auto-Modus (Nano Banana mit Referenzbild 40 Tokens); Bilder öffentlich
- K9 (11.10.2026): Gemini 5 · ChatGPT 5 · Leonardo.Ai 2 (Ziffer 8.7 vs. Hilfe-Artikel); Quellen-Links: policies.google.com/terms?hl=de-CH · support.google.com/gemini/answer/13594961?hl=de · openai.com/policies/eu-terms-of-use/ · help.openai.com/de-de/articles/7730893-data-controls-faq · leonardo.ai/terms-of-service/ · intercom.help/leonardo-ai/en/articles/8044018-commercial-usage
- Skript M306 zum Projektabschluss: Kap. 5.3 (Phase Projektabschluss: Übergabe inkl. Dokumentation, Schulung der Benutzer, Nachkalkulation, Debriefing/Lessons learned; Resultat Abnahmeprotokoll), Kap. 2.1 (beste Aufwandschätzungen zu Projektende, Erfahrungswerte), Kap. 2.2 (Nachkalkulation, Schätzungsabweichungen i.d.R. ±50 %), Kap. 2.5.5 (tatsächliche Zeiten im Gantt nachtragen)
- Modultitel laut Modulbaukasten (modulbaukasten.ch/assets/module/Moduluebersicht-DE-V3.pdf, Abruf 12.10.2026): 306 «Kleinprojekte im eigenen Berufsumfeld abwickeln», 426 «Software mit agilen Methoden entwickeln», 431 «Aufträge im eigenen Berufsumfeld selbständig durchführen»
