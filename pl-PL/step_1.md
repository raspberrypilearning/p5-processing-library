Biblioteka p5 umożliwia tworzenie rysunków, animacji i prostych gier.

--- code ---
---
language: python filename: main.py line_numbers: true
line_number_start: 4
---

from p5 import *

--- /code ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0; font-weight: bold;">Biblioteka p5</span> udostępnia funkcje graficzne do rysowania, animacji i wizualizacji danych. Artyści, animatorzy i projektanci używają biblioteki przetwarzania p5 do kreatywnego kodowania.</p>

Istnieją dwie funkcje, które każdy projekt używający `p5` musi **zdefiniować**:
+ **setup()** - uruchamia się raz, gdy program zaczyna ustawiać właściwości, takie jak rozmiar ekranu
+ **draw()** - uruchamia się wielokrotnie i określa, co zostanie naszkicowane

Musisz także **wywołać** funkcję `run()`:
+ **run()** - uruchamia projekt p5, wywołując funkcję `setup()`, a następnie wielokrotnie wywołując funkcję `draw()`
