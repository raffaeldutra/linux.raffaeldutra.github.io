# cp

O comando __`cp`__ por padrão, é usado para copiar arquivo. Mas, com o uso de parâmetro, pode ser usado também para copiar diretório.

## Sintaxe Básica

```
cp arquivo.txt /home/username/documents
```

O parâmetro `-v` logo após o `cp` permite reproduzir em tela um resultado, tal como abaixo:

```
cp -v arquivo.txt /home/username/documents
```

com o seguinte resultado:

```
'arquivo.txt' -> '/home/username/documents/arquivo.txt'
```

## Copiar diretório inteiro 

Para copiar um diretório inteiro para outro diretório é necessário o parâmetro `-r`:

__`cp -r`__ caminho/de/origem caminho/de/destino

### Exemplo

```
cp -r /home/username/documents /home/username2/documents_backup
```

Para reproduzir em tela esse resultado, é preciso adicionar ao `_cp_` o parâmetro `_-rv_`

```
cp -rv /home/username/documents /home/username2/documents_backup
```
com o seguinte resultado:

```
'/home/username/documents' -> '/home/username2/documents_backup/documents'
```

## Copiar arquivo/diretório

Para copiar, seja arquivo ou diretório, e ainda manter as permissões, grupo e dono, pode ser usado o parâmetro `-a`:

__`cp -a`__ caminho/de/origem caminho/de/destino

### Exemplo

```
cp -a /home/username/documents /home/username2/documents_backup
```

Para reproduzir em tela esse resultado, é preciso adicionar ao `_cp_` o parâmetro `_-av_`

```
cp -av /home/username/documents /home/username2/documents_backup
```

com o seguinte resultado:

```
'/home/username/documents' -> '/home/username2/documents_backup/documents'
```