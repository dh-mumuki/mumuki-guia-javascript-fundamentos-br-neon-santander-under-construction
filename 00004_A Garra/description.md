Como você pode ver abaixo, o novo tabuleiro que geramos tem uma célula marcada:

<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>

Por que isso acontece? Porque em nosso tabuleiro teremos uma máquina que possui uma **garra** que em todos os momentos estará localizada em alguma das células do tabuleiro, isso irá nos permitir executar várias operações sobre ele,  (iremos conhecer, paciência  :grin:).

Algo importante: observe que contamos as linhas de baixo para cima e as colunas da esquerda para a direita. A primeira **linha** é a **inferior** e a primeira **coluna** é a da **esquerda**. Mas também, se você prestar atenção, verá que a primeira linha é **zero** e a primeira coluna também é **zero**. Isto é assim porque em todas as linguagens de programação sempre começamos a contar do **zero**.



Por exemplo, abaixo temos um tabuleiro de 5x2, com a garra na segunda linha (linha número 1) e a quarta coluna (coluna número 3).


<gs-board>
  GBB/1.0
    size 5 2
    head 3 1
</gs-board>
