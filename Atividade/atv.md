# Variaveis
- declaracao de variaveis
- escopo
  - global
  - bloco
  - funcao

# Tipos de dados
- objeto
- array
- tipos primitivos
  - booleon
  - string
  - null
  - number
  - undefined
  
# Operadores basicos
- aritmeticos
- de comparacao
- logicos
- typeof

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
- Usando valores undefined, valor padrao quando uma variavel é declarada, mas nao inicializada
EXEMPLO
```JavaScript
let indefinido;
console.log(typeof indefinido);
```
---
- Usando valores null, indica a ausencia de valor intencionalmente 
EXEMPLO
```JavaScript
let nulo=null;
console.log(typeof nulo);
```
---
>## EXPLICACAO ADICIONAL
---
``boolean``:usado para representar valores logicos verdadeiros ou falso.
---
``number`` :usado para representar valores numericos, tanto inteiros quanto de ponto flutuante.
---
``string``:usado para representar sequencias de caracteres
---
``undefined`` :indica que uma variavel foi declarada, mas ainda nao foi atribuida com um valor.
---
``null``:indica explicitamente a ausencia de valor.
---
>- EXERCICIO
### 1.marque 'X' para a alternativa 'ERRADA'.
- [ ] valores nulos indicam a ausencia de valores.
- [X] valores de var sao apenas declaradas localmente.
- [ ] valores let sao apenas declarados localmente.
- [ ] valores string sao usados para representar um texto
- [ ] em escopo global, as variaveis podem ser declaradas fora de uma funcao 

>[TIPOS DE DADOS]
- ``Objetos``: em javascript os objetos sao declarados por meio das chaves com valores, podendo ser qualquer tipo de valor
EXEMPLO
```JavaScript
let carro ={
    marca:"nissan",
    modelo:"sentra",
    ano:2021,
    cor:"prata"
  };
  console.log(carro.marca);
  console.log(carro.modelo);
  console.log(carro.ano);
  console.log(carro.cor);
```
---
``Array`` :O array é como se fosse uma lista, possuindo cada caracteristicas que podem ser adicionadas e modificadas

