# su

O comando __`su `__ significa `__s__uper __u__ser`. É o usuário root. Ele tem superpoderes para executar comandos.

## Sintaxe Básica

```
su
```

## Com o seguinte resultado:

```
fernanda@base:/$ su
```

Ao executar o comando _`su`_ será solicitada uma senha.

## Com o seguinte resultado:

```
Senha:
```

A senha a ser digitada é a senha de root.

## Com o seguinte resultado:

```
root@base:/home/fernanda#
```

Ou seja, o usuário agora se tornou root, mas tem acesso às próprias configurações, não às configurações do root.

# su -

O comando __`su -`__ é o comando __`su`__ com o parâmetro __`-`__. 

Este parâmetro dá ao usuário, acesso a comandos de usuário root. Mas com a diferença de trazer consigo acesso às configurações do root.

## Sintaxe Básica

```
 _`su -`_ 
```

## Com o seguinte resultado:

```
fernanda@base:/$ su -
```
Ao executar o comando  _`su -`_ será solicitada uma senha.

## Com o seguinte resultado:

```
Senha:
```

A senha digitada é a senha de root.

## Com o seguinte resultado:

```
root@base:~#
```

Podemos perceber visualmente a diferença ao executar o comando  _`su`_ e em seguida o comando _`adduser`_

```
fernanda@base:~$ su
```

Será solicitada senha

```
Senha:
```
Digitar a senha de root

## Com o seguinte resultado:

```
root@base:/home/fernanda#
```
Executar o comando _`adduser`_

```
root@base:/home/fernanda# adduser
```
## Com o seguinte resultado:

```
bash: adduser: comando não encontrado
```
Mas se executarmos o comando _`su -`_ e em seguida o comando _`adduser`_ 

```
fernanda@base:~$ su -
```

Será solicitada senha

```
Senha:
```
Digitar a senha de root

## Com o seguinte resultado:

```
root@base:~# 
```
Executar o comando _`adduser`_

```
root@base:~# adduser fulano
```
## Com o seguinte resultado:

```
Adicionando usuário 'fulano' ...
```
Ou seja:

Com o _`su`_ preciso passar o path para ele encontrar o comando, visto que estou como root mas sem acessar as configurações dele

Mas com o _`su -`_ vou estar como root acessando as configurações do próprio root, e não há necessidade de passar o path para que o comando seja encontrado.
