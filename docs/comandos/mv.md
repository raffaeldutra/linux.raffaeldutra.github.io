# mv

O comando __`mv`__ é utilizado para mover ou renomear arquivos e diretórios.
## Sintaxe básica
```
mv <origem> <destino>
```
## Mover/renomear

Para mover/renomear um arquivo/diretório, basta acrescentar depois do __`mv`__ dois argumentos:

Argumento 1: A origem do nome do arquivo/diretório, por exemplo `/home/username/arquivo.txt` ou `/home/username/diretorio`

Argumento 2: O destino do arquivo/diretório, por exemplo
`/home/username/arquivo2.txt` ou `/home/username/diretorio2`
### Exemplo
```
mv arquivo.txt /home/username/documents
```
No exemplo acima, como não foi especificado o nome do arquivo de destino em `/home/username/documents`, automaticamente será assumido que o arquivo manterá o nome, neste caso, `arquivo`
## Mudar o nome no destino

Para mudar o nome no destino, deve vir especificado o novo nome.
### Exemplo
```
mv /home/username/arquivo.txt /home/username/documents/arquivo2.txt
```