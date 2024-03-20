# Variaveis
- declaracao de variaveis
- escopo
  - global
  - bloco
  - funcao

# Tipos de dados
- objeto
- tipos primitivos
  - booleon
  - string
  - null
  - number
  - undefined

---
  ## Declaracao de variaveis
  >[!TIPOS DE VARIAVEIS]

  Para declarar variaveis no javascript é usado o`Var`, `let` e o `const`

  - usando o `var`é possivel declarar a variavel globalmente ou localmente para uma funçao

- EXEMPLO
```JavaScript
var variavel = 10;
function varia(){
    var variavel2=11;
}
```
---

   - usando o `let` é possivel declarar a variavel localmente para um bloco

- EXEMPLO
``` JavaScript
function(){
    let variavel=12;
}
```
---
  - usando o `const`declarar uma constante localmente para um bloco (valor nao pode ser alterado)

- EXEMPLO
```JavaScript
function(){
    const variavel=13;
}
```
---
>[!ESCOPO]

OBS:Em JavaScript existem dois tipos de escopo(escopo é a acessibilidade e visibilidade de variaveis e funcoes em diferentes partes do codigo), o escopo global e o local.

- Escopo Global: as variaveis declaradas fora de qualquer funcao tem escopo global, elas podem ser acessadas em qualquer lugar no codigo.

- Escopo Local: as variaveis declaradas dentro de uma funcao tem escopo local. elas so podem ser acessadas dentro dessa funcao
---

## Tipos De Dados
>[!TIPOS PRIMITIVOS]
---
- Usando valores boolean, é possivel definir `true` e `false``
EXEMPLO:
```JavaScript
let booleano= true;
console.log(typeof booleano);
```
---
- Usando valores number, pode conter numeros inteiros ou de ponto fluente 
EXEMPLO:
```JavaScript
let numero=14;
console.log(typeof numero)
```
---
- Usando sequencia de caracteres entre aspas simples ou duplas
EXEMPLO
```JavaScript
let texto='variavel';
console.log(typeof texto);
```
---
- Usando 




