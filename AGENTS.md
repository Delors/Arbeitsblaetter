# AGENTS.md – Arbeitsblätter erstellen

Allgemeine Hinweise für das Erstellen neuer Arbeitsblätter in diesem Repository. Diese Datei gilt für alle künftigen Arbeitsblätter.

## Ablageort

- Jedes Arbeitsblatt kommt in das passende Verzeichnis: `<Klassenstufe>/<Fach>/`, z. B. `6. Klasse/Deutsch/` oder `3. Klasse/Mathe/`.
- Vor dem Erstellen immer die vorhandenen Dateien im selben Ordner lesen und deren Aufbau/Stil übernehmen.

## Dateiformat

- Bevorzugt **Markdown** (`.md`).
- Nur wenn Grafiken nötig sind, **HTML** mit inline **SVG** erzeugen.
- Dateinamen ohne Umlaute (ASCII), Namenskonvention:
  - Arbeitsblatt: `<Thema>_Arbeitsblatt.md`
  - Lösungen: `<Thema>_Arbeitsblatt_Loesungsvorschlaege.md`

## Inhalt und Aufbau

- **Keine Felder für Name, Klasse, Datum** einbauen – nur das Arbeitsblatt selbst.
- Jedes Arbeitsblatt beginnt mit einer **kurzen Einführung mit Beispielen** (z. B. Abschnitt „Das lernst du" und/oder ein Merkkasten mit Beispielssätzen/-tabellen).
- Abschnitte mit `##` / `###`, Aufgaben nummeriert als „Aufgabe N:".
- Lösungszeilen für Schülerinnen und Schüler als `\________________________________________________________________`.
- Hervorhebungen mit **fett**, Beispieltexte als Blockzitat (`>`).
- In Mathe-Arbeitsblättern Zahlen in KaTeX `$...$` setzen; in Deutsch-Arbeitsblättern weitgehend Klartext.
- Sprache: Deutsch, schülergerecht; Schwierigkeit innerhalb eines Blatts steigern (leicht → mittel → schwer/knifflig).

## Lösungen

- Zu **jedem** Arbeitsblatt eine separate Lösungsdatei anlegen.
- In der Lösungsdatei oben ein kurzer Hinweis: Lösungen sind Musterlösungen; bei offenen Schreibaufgaben sind andere passende Antworten ebenfalls möglich.
- Antworten fett hervorheben.

## Qualität

- Alle fachlichen Inhalte (Rechtschreibung, Grammatik, Rechenlösungen) sorgfältig prüfen – die Blätter werden KI-unterstützt erstellt, aber kontrolliert (siehe README).
