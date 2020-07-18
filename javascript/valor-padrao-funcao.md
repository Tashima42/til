# Valor padrão em uma função
Em uma função, algumas vezes é esperado que caso um parâmetro não seja declarado, ele assuma um valor padrão. Isso pode ser feito de várias maneiras, mas a mais atual, introduzida no ES6 é a seguinte:
```js
function soma(a = 1, b = 2, c = 4){
    //...
}
```
Ao atribuir valores a um parâmetro, quando a função for chamada e nada for atribuido a ele, assumirá o valor padrão.