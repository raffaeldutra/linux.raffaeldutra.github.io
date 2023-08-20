# Comandos para Linux

Projeto para comandos Linux.

## Criando novo site

```bash
docker container run \
--rm \
-it \
-v $(pwd):/docs \
squidfunk/mkdocs-material:9 new .
```

## Rodando servidor

```bash
docker container run \
--rm \
-it \
-p 8000:8000 \
-v $(pwd):/docs \
squidfunk/mkdocs-material:9
```