Agora que estamos combinando operações, e como comentamos previamente, teremos que ter mais cuidado com a ordem dos comandos.

> Tendo isso em mente, responda ... O que esses programas fazem?


```gobstones
program {
  Mover(Leste)
  Colocar(Vermelho)
  Colocar(Preto)
}
```

```gobstones
program {
  Colocar(Preto)
  Mover(Leste)
  Colocar(Vermelho)
}
```
