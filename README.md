# HaeufigkeitsPunktPlot

Teilergebnis meines Semesterprojektes "Visualisierungsmethoden":

Erzeugt einen Punkt-Plot der Häufungen von Datenpunkten, die auf den gleichen x-y Koordinaten liegen, berücksichtigt.
Dies tritt gerade bei Statistiken mit Skalenniveau häufig auf. 
Diese Überlappung wird durch eine proportional skalierende Punktgröße, sowie eine passende Färbung, dargestellt.

Hinweis zur Struktur des Excel-Dokuments:
  1. Die erste Spalte muss ein ganzzahliger Index des Datensatzes sein (z.B eine fortlaufende Teilnehmernummer)
  2. Die Spalten die als x bzw. y Achse geplottet werden sollen müssen gleichviele Einträge haben und in der Konfiguration angegeben werden (siehe Anleitung) 

Anleitung (Für Nicht-Informatiker gedacht):
  1. Projekt auf dieser Github-Seite herunterladen
       -> "Code <>"
       -> "Zip herunterladen"
       -> Zip Datei entpacken
  2. Projekt in Google Colab hochladen
       -> In Google Colab (https://colab.research.google.com/?hl=de) anmelden. Google Konto ist erforderlich!
       -> In Google Colab auf "Hochladen" klicken und die "ExelHäufigkeitsPlotter.ipynb" Datei auswählen
       -> "Konfiguration.json" mit einem beliebigen Textprogramm öffnen und passend zu Ihrem Datensatz ausfüllen. Beispielwerte sind enthalten.
       -> In der geöffneten Datei in Google Colab das Ordner-Symbol am linken Rand klicken
       -> Die Konfigurationsdatei Über das Upload-Symbol unter "Dateien" hochladen
       -> Anschließend die Exceldatei mit den Daten auf dem selben Weg hochladen
  3. Visualisieren
       -> "Strg" und "9" gleichzeitig drücken, um das ganze Projekt auszuführen.
       -> Graphik über klick auf das Ordner Symbol am linken Rand suchen.
       -> Rechtsklick auf die Bilddatei und "herunterladen" auswählen.
       -> Fertig
       


