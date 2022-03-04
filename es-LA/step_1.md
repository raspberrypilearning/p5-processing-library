La biblioteca p5 te permite crear dibujos, animaciones y juegos sencillos.

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
La <span style="color: #0faeb0; font-weight: bold;"> biblioteca p5 </span> proporciona funciones gráficas para dibujo, animación y visualización de datos. Artistas, animadores y diseñadores utilizan la biblioteca de procesamiento p5 para hace una codificación creativa.</p>

Hay dos funciones que cada proyecto en el que se usa `p5` necesita **definir**:
+ **setup()** - se ejecuta una única vez cuando el programa comienza para configurar propiedades como el tamaño de la pantalla
+ **draw()** - se ejecuta repetidamente y define lo que se dibujará

También necesitarás **llamar** a la función `run()`:
+ **run()** - inicia el proyecto p5 primero llamando a la función `setup()` y luego llamando repetidamente a la función `draw()`

