Neste exercício aprenderemos um comando que podemos dar ao computador: 
“Mover a garra". Para isso, indicaremos com base nos pontos cardeais a direção que este irá mover:

* Norte (acima)
* Sul (abaixo)
* Leste (direita)
* Oeste (esquerda)


Por exemplo, partindo de um tabuleiro **inicial** vazio, podemos facilmente escrever um programa que mova a garra à posição “Norte”:

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
        head 0 1
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>

O **código** do programa que faz isso (ou seja, o **texto** da solução que damos ao computador) é o seguinte:

```gobstones
program {
  Mover(Norte)
}
```

:eyes:  
Observe que as direções sempre são escritas com  a primeira letra maiúscula.

> Não acredita? Copie e cole o código anterior no editor e envie.  **Enviar**.
