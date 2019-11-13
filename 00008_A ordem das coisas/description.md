Quando trabalhamos no Gobstones, fazemos as coisas em uma determinada ordem. Por exemplo, vamos pensar que, dada a próxima casa inicial, queremos mover a garra para o canto nordeste:

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 3 3
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        head 2 2
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

Se temos o seguinte programa:

```gobstones
program {
  Mover(Norte)
  Mover(Norte)
  Mover(Leste)
  Mover(Leste)
}
```

Uma forma possível de lê-lo (chamada **sequencial**) é como uma máquina faria: em ordem, de cima para baixo:

1. Primeiro se move ao norte: `Mover(Norte)`
1. Então se move ao norte novamente: `Mover(Norte)`
1. Então se move ao leste: `Mover(Leste)`
1. E finalmente se move a leste mais uma vez: `Mover(Leste)`

E de fato **é executado dessa maneira**.

Mas, nós humanos tendemos a pensar em termos do resultado final, isto é, enfatizamos o **objetivo** do programa. Nós nos preocupamos mais com o que ele faz, e não tanto como se faz. Essa maneira de pensar nos levaria a dizer, simplesmente, **mover a garra para o canto nordeste**.


Por isso há várias formas de resolver um mesmo problema: podemos escrever vários programas que faça o mesmo (o _que_), mas faça diferente (o _como_).


> Escreva outro programa que faz o mesmo que o anterior (move-se para o canto nordeste), mas de uma maneira diferente. Tem que trabalhar em um tabuleiro 3x3.