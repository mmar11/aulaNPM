# Testando meu primeiro módulo NPM
- ola(nome):  
  Essa função imprime uma saudação.

Como usar?
```shel

npm install dh-meumodulo-testeaula
```

```js
const meuModulo = require("dh-meumodulo-testeaula")
const resultado = meuModulo.ola('Meu nome')
console.log(resultado) // Olá Meu nome, você está usando o pacote criado by Marcelo Mariano
```
