p5ライブラリを使用すると、図、アニメーション、および簡単なゲームを作成できます。

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
<span style="color: #0faeb0; font-weight: bold;"> p5ライブラリ </span> は、図、アニメーション、およびデータ視覚化のためのグラフィック機能を提供します。 アーティスト、アニメーター、およびデザイナーは、p5 Processingライブラリを使用して創造的コーディングを行います。</p>

`p5`を使用するプロジェクトはいずれも2つの関数を**定義**する必要があります。
+ **setup()** - 画面サイズなどのプロパティを設定するために、プログラムの開始時に1回だけ実行されます
+ **draw()** - 繰り返し実行され、何を描くか定義します

また、`run()`関数を**呼び出す**ことも必要です。
+ **run()** - `setup()`関数を呼び出してp5プロジェクトを開始し、 `draw()`関数を繰り返し呼び出します

