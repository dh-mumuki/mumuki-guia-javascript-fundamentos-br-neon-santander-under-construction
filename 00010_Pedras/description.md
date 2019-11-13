Genial :smile:

Você já entendeu como mover a garra do tabuleiro usando a operação “Mover” e as direções (Norte, Sul, Leste e Oeste). Vamos um passo além com as “pedrinhas”. Em qualquer célula do nosso tabuleiro, podemos colocar "pedrinhas" com diferentes cores:

 * Vermelhas (`Vermelho`)
 * Azuis (`Azul`)
 * Pretas (`Preto`)
 * Verdes (`Verde`)

Por exemplo, este é um tabuleiro com uma bola vermelha e uma bola preta:


<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>



Além de se mover, a garra também pode colocar pedras na célula onde está. Para isso temos a operação 'Colocar', que diz à garra para depositar uma pedra da cor dada:

```gobstones
program {
  Colocar(Vermelho)    
}
```


> Experimente este programa! Escreva o código no editor para colocar uma pedrinha vermelha no tabuleiro e clique em **Enviar** para ver o que acontece quando é executado.

<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>
