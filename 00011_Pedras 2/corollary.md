Note que nesse problema, se mudarmos a ordem das instruções, o resultado não muda: sempre teremos uma célula com três pedras vermelhas, uma azul e outra verde.


Por exemplo, os dois programas a seguir também geram esse mesmo resultado:


```gobstones
program {
  Colocar(Vermelho)
  Colocar(Vermelho)
  Colocar(Vermelho)
  Colocar(Verde)
  Colocar(Azul)
}
```

```gobstones
program {
  Colocar(Vermelho)
  Colocar(Azul)
  Colocar(Vermelho)
  Colocar(Verde)
  Colocar(Vermelho)
}
```
