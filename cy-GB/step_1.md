Mae'r llyfrgell p5 yn gadael i chi greu lluniadau, animeiddiadau a gemau syml.

--- code ---
---
language: python filename: main.py line_numbers: true
line_number_start: 4
---

from p5 import *

--- /code ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Mae'r <span style="color: #0faeb0; font-weight: bold;">llyfrgell p5</span> yn darparu swyddogaethau graffeg ar gyfer llunio, animeiddio a delweddu data. Mae artistiaid, animeiddwyr a dylunwyr yn defnyddio Llyfrgell brosesu p5 ar gyfer codio creadigol.</p>

Mae dwy swyddogaeth y mae pob prosiect sy'n defnyddio `p5` angen eu **diffinio**:
+ **setup()** - yn rhedeg unwaith pan fydd y rhaglen yn dechrau i osod priodweddau fel maint sgrin
+ **draw()** - yn rhedeg dro ar ôl tro ac yn diffinio beth fydd yn cael ei lunio

Mae angen i chi **alw'r** swyddogaeth `run()` hefyd:
+ **run()** - yn dechrau'r prosiect p5 drwy alw'r swyddogaeth `setup()` cyn galw'r swyddogaeth `draw()` dro ar ôl tro
