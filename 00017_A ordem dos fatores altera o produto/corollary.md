Moral: eles não fazem o mesmo! Mudar a ordem mudou o objetivo, isto é, o ‘o quê’.

O primeiro programa


```gobstones
program {
  Mover(Leste)
  Colocar(Vermelho)
  Colocar(Preto)
}
```
sequencialmente:

1. Se move para leste
1. Põe uma pedra vermelha
1. Põe uma pedra preta

Ou seja, coloca uma pedra vermelha e uma pedra preta a leste da posição inicial.

Enquanto o segundo programa

```gobstones
program {
  Colocar(Preto)
  Mover(Leste)
  Colocar(Preto)
}
```
sequencialmente:

1. Põe uma pedra preta
1. Se move para leste
1. Põe uma pedra vermelha

Ou seja: põe uma pedra preta na posição inicial e uma pedra vermelha a leste da pedra preta.