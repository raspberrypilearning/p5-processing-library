تتيح لك مكتبة p5 إنشاء رسومات و الرسوم المتحركة وألعاب بسيطة.

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
توفر <span style="color: #0faeb0; font-weight: bold;"> p5 library </span> وظائف رسومية للرسم والرسوم المتحركة وتمثيل البيانات. يستخدم الفنانون ورسامو الرسوم المتحركة والمصممين مكتبة المعالجة p5 لكتابة شفرة برمجية بشكل إبداعي.</p>

هناك دالتين كل مشروع يستخدم `p5` يحتاج الى **define**:
+ **setup()** - يعمل مرة واحدة عندما يبدأ البرنامج في ضبط الخصائص مثل حجم الشاشة
+ **draw()** - يعمل بشكل متكرر ويحدد ما سيتم رسمه

تحتاج أيضًا إلى **call** الدالة `run()`:
+ **run()** - يبدأ مشروع p5 باستدعاء الدالة `setup()` متبوعة باستدعاء الدالة `draw()` بشكل متكرر

