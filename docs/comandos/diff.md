# diff

O comando __`diff`__ é utilizado para comparar arquivos entre sí.

Digite __`diff`__ seguido do nome de cada arquivo que deseja comparar.

## Sintaxe Básica

```
diff arquivo1 arquivo2
```

## Exemplo

Para testar a aplicação do comando, alterei dois arquivos texto e após, executei o comando `diff`.

observei o seguinte resultado:

```
1,2c1,2
< Este é um arquivo teste.
---
> batata
> arroz
```

No caso acima, o sinal de menor `<` indica o que saiu e o sinal de menor `>` indica o que entrou, com a modificação feita em cada um dos arquivos.