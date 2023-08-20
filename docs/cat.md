# cat

O comando __`cat`__ mostra em tela o resultado.

Permite:

* ver
* criar
* relacionar arquivos

## Sintaxe básica

```
cat arquivo.txt
```

com o seguinte resultado:

```
{
  "name": "prime",
  "version": "0.1.0",
  "private": true,
  "dependencies": {
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-scripts": "5.0.1",
    "web-vitals": "^2.1.4"
....
....
```

## Mostrar linhas

```
cat -b arquivo.txt
```

com o seguinte resultado:

```
     1  {
     2    "name": "prime",
     3    "version": "0.1.0",
     4    "private": true,
     5    "dependencies": {
     6      "@testing-library/jest-dom": "^5.16.5",
     7      "@testing-library/react": "^13.4.0",
     8      "@testing-library/user-event": "^13.5.0",
     9      "react": "^18.2.0",
    10      "react-dom": "^18.2.0",
    11      "react-scripts": "5.0.1",
    12      "web-vitals": "^2.1.4"
....
....
```