La bibliothèque p5 te permet de créer des dessins, des animations et des jeux simples.

--- code ---
---
language: python filename: main.py line_numbers: true
line_number_start: 4
---

from p5 import *

--- /code ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
La <span style="color: #0faeb0; font-weight: bold;">bibliothèque p5 </span> fournit des fonctions graphiques pour le dessin, l'animation et la visualisation de données. Les artistes, les animateurs et les concepteurs utilisent la bibliothèque de traitement p5 pour le codage créatif.</p>

Il y a deux fonctions dont chaque projet utilisant `p5` a besoin pour **définir** :
+ **setup()** - s'exécute une fois lorsque le programme commence à définir des propriétés telles que la taille de l'écran
+ **draw()** - s'exécute à plusieurs reprises et définit ce qui sera dessiné

Tu dois aussi **appeler** la fonction `run()` :
+ **run()** - démarre le projet p5 en appelant la fonction `setup()` suivie d'un appel répété à la fonction `draw()`
