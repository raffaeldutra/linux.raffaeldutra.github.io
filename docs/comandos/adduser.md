# adduser

O comando __`adduser`__ adiciona um usuário ao sistema.

Normalmente é utilizado acompanhado do comando `sudo`.

## Sintaxe básica

Por exemplo, para criar um usuário fulano:

```
sudo adduser aluno
```

com o seguinte resultado:

```
Adding user `aluno' ...
Adding new group `aluno' (1005) ...
Adding new user `aluno' (1005) with group `aluno (1005)' ...
Creating home directory `/home/aluno' ...
Copying files from `/etc/skel' ...
New password:
Retype new password:
passwd: password updated successfully
Changing the user information for aluno
Enter the new value, or press ENTER for the default
        Full Name []: aluno
        Room Number []:
        Work Phone []:
        Home Phone []:
        Other []:
Is the information correct? [Y/n] Y
Adding new user `aluno' to supplemental / extra groups `users' ...
Adding user `aluno' to group `users' ...
```