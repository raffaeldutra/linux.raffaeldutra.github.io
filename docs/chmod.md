# chmod

O comando __`chmod`__ é utilizado para mudar as permissões do arquivo.

Em Linux, cada arquivo está associado a três classes de usuários:

* proprietário
* membro do grupo
* outros

Se o proprietário for o único com permissões totais, podemos alterar o arquivo para permitir que os membros e outros possam ler, gravar e executar o arquivo.

## Sintaxe Básica

No exemplo abaixo, cada número da sequência numérica entre o chmod e o nome do arquivo define um nível de permissão para ler, para gravar e para executar:

```
chmod 777 arquivo.txt
```