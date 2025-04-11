Knihovna p5 umožňuje vytvářet kresby, animace a jednoduché hry.

--- code ---
---
language: python filename: main.py line_numbers: true
line_number_start: 4
---

from p5 import *

--- /code ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Knihovna <span style="color: #0faeb0; font-weight: bold;"> p5 </span> poskytuje grafické funkce pro kreslení, animaci a vizualizaci dat. Umělci, animátoři a designéři používají knihovnu p5 Processing pro kreativní kódování.</p>

Existují dvě funkce, které každý projekt používající `p5` potřebuje **definovat**:
+ **setup()** - spustí se jednou, když program začne nastavovat vlastnosti, jako je velikost obrazovky
+ **draw()** - spouští se opakovaně a definuje, co bude načrtnuto

Také musíte **zavolat** funkci `run()`:
+ **run()** - spustí projekt p5 voláním funkce `setup()` a následným opakovaným voláním funkce `draw()`
