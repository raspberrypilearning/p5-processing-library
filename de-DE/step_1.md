Mit der p5 Bibliothek kannst Du Zeichnungen, Animationen und einfache Spiele erstellen.

--- code ---
---
language: python filename: main.py line_numbers: true
line_number_start: 4
---

from p5 import *

--- /code ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Die <span style="color: #0faeb0; font-weight: bold;"> p5-Bibliothek </span> bietet grafische Funktionen zum Zeichnen, Animieren und um Daten darzustellen. Künstler, Trickfilmkünstler und Designer nutzen die p5 Verarbeitungsbibliothek für kreatives Programmieren.</p>

Es gibt zwei Funktionen, die in jedem `p5`-Projekt **definiert** sein müssen:
+ **setup()** – wird einmal ausgeführt, wenn das Programm beginnt um Eigenschaften wie die Bildschirmgröße festzulegen
+ **draw()** – wird wiederholt ausgeführt und legt fest, was gezeichnet wird

Du musst auch die Funktion `run()` **aufrufen**:
+ **run()** – startet das p5-Projekt durch Aufrufen der Funktion `setup()` und ruft anschließend wiederholt `draw()` auf
