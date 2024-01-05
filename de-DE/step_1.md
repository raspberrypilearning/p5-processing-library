The p5 library allows you to create drawings, animations and simple games.

--- code ---
---
language: python filename: main.py line_numbers: true
line_number_start: 4
---

from p5 import *

--- /code ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
The <span style="color: #0faeb0; font-weight: bold;"> p5 library </span> provides graphic functions for drawing, animation and data visualisation. Artists, animators and designers use the p5 Processing library for creative coding.</p>

There are two functions that every project using `p5` needs to **define**:
+ **setup()** - runs once when the program starts to set properties like screen size
+ **draw()** - runs repeatedly and defines what will be sketched

You also need to **call** the `run()` function:
+ **run()** - starts the p5 project by calling the `setup()` function followed by repeatedly calling the `draw()` function
