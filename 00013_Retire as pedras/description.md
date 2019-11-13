Da mesma forma que se pode dar o comando para "colocar a pedra" ("Colocar"), temos uma forma de "retirar a pedra" ("Retirar"), que remove exatamente uma pedra da cor dada.

Por exemplo, o programa a seguir retira duas pedras vermelhas da posição inicial.

```gobstones
program {
  Retirar(Vermelho)
  Retirar(Vermelho)
}
```
> Sabendo disso, escreva um programa que remova **apenas** a pedra vermelha deste tabuleiro. **Tenha cuidado!** Preste atenção para a posição da garra.:wink:

<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>
