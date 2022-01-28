Met de p5-bibliotheek kun je tekeningen, animaties en eenvoudige spelletjes maken.

--- code ---
---
language: python filename: main.py line_numbers: true
line_number_start: 4
---

from p5 import *

--- /code ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
De <span style="color: #0faeb0; font-weight: bold;"> p5 bibliotheek </span> biedt grafische functies voor tekenen, animeren en datavisualisatie. Kunstenaars, animators en ontwerpers gebruiken de p5 ontwerpbibliotheek voor creatieve codering.</p>

Er zijn twee functies die je in elk project dat gebruik maakt van `p5` moet **definiëren**:
+ **setup()** - wordt één keer uitgevoerd wanneer het programma begint met het instellen van eigenschappen zoals schermgrootte
+ **draw()** - wordt herhaaldelijk uitgevoerd en definieert wat er wordt getekend

Je hebt ook de **aanroep** van functie `run()` nodig:
+ **run()** - start het p5-project door de functie `setup()` aan te roepen, gevolgd door herhaaldelijk aanroepen van de functie `draw()`
