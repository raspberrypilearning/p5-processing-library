La libreria p5 ti permette di creare disegni, animazioni e piccoli giochi.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 4
---

from p5 import *

--- /code ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
La <span style="color: #0faeb0; font-weight: bold;">libreria p5</span> fornisce funzioni grafiche per il disegno, l'animazione e la visualizzazione dei dati. Gli artisti, gli animatori e i designer utilizzano la libreria di elaborazione p5 per il coding creativo.</p>

Ci sono due funzioni che ogni progetto che utilizza `p5` deve **definire**:
+ **setup()** - viene eseguito solo una volta, quando il programma inizia a impostare proprietà come la dimensione dello schermo
+ **draw()** - viene eseguito ripetutamente e definisce cosa verrà disegnato

È inoltre necessario **chiamare** la funzione `run()`:
+ **run()** - avvia il progetto p5 chiamando la funzione `setup()` quindi chiama ripetutamente la funzione `draw()`
