# Template String
Template strings são literais, que permitem expressões e quebra de linha, permitindo também interpolação de strings.
São delimitados por ` `` ` e expressões são declaradas com `${}`.

**_Código_**
```js
const numero = 1903
const templateString = `Essa é uma template 
string, ${numero}`

console.log(templateString)
```
**_resultado_**
```
Essa é uma template 
string, 1903
```