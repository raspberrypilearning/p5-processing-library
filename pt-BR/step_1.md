A biblioteca p5 permite criar desenhos, animações e jogos simples.

--- code ---
---
language: python filename: main.py line_numbers: true
line_number_start: 4
---

from p5 import *

--- /code ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
A biblioteca <span style="color: #0faeb0; font-weight: bold;"> p5 </span> oferece funções gráficas para desenho, animação e visualização de dados. Artistas, animadores e designers usam a biblioteca de processamento p5 para codificação criativa.</p>

Existem duas funções que todo projeto usando `p5` precisa **definir**:
+ **setup()** - executa uma vez quando o programa começa a definir propriedades como tamanho da tela
+ **draw()** - executa repetidamente e define o que será esboçado

Você também precisa **chamar** a função `run()`:
+ **run()** - inicia o projeto p5 chamando a função `setup()` e em seguida chama repetidamente a função `draw()`
