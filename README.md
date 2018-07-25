# Aprenda ES6 (JavaScript)

## Introdução

### Funções de Primeira Classe

### ES6 `const` e `let`

- Uma variável declarada com `const`não pode ser ter um novo valor atribuído a ela.

```js
// não permitido
const helloWorld = 'Welcome to ES6';
helloWorld = 'Bye Bye ES6';
```

- Uma variável declarada com `let` pode ter o seu valor alterado.

```js
// permitido
let helloWorld = 'Welcome to ES6';
helloWorld = 'Bye Bye ES6';
```

- Porém, quando a variável estiver dentro de um array ou de um objeto criados com `const`, o valor dela pode ser alterado.

```js
// permitido
const helloWorld = {
    text: 'Welcome to ES6';
};
helloWorld.text = 'Bye Bye React';
```

**Dica:** Como padrão deve-se usar sempre `const` para declarar as variáveis em ES¨. Usar `let` somente quando precisar que o valor da variável seja mutável.

- [const - Referência JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/const)
- [let - Referência JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/let)

### Closures

### Immutable Data Structures

- Por quê elas fazem sentido na programação em geral?

### map

[Array.prototype.map() - JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
[map(), filter() e reduce() em JavaScript](http://desenvolvimentoparaweb.com/javascript/map-filter-reduce-javascript/)

### ES6 Arrow Functions

- **Sintaxe:**

```js
// function expression
function () { ... }

// arrow function expression
() => { ... }
```

**Atenção:** Ficar atento para o comportamento do objeto `this` em uma arrow function

- **Parêntesis e argumentos:**

- Quando houver um só argumento na função, o uso de parêntesis não é obrigatório
- Quando houver mais de um argumento, o uso de parêntesis é obrigatório

```js
//permitido
item => { ... }

// permitido
(item) => { ... }

// não permitido
item, key => { ... }

// permitido
(item, key) => { ... }
```

- **Block body e concise body:**

- Block body: Utiliza o `return { ... }` após a declaração da arrow function
- Concise body: Não utiliza o `return { ... }` após a declaração da arrow function

[Arrow Functions - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

### Classes

[ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

### Object Initializer

- [Object Initializer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer)
- [Computed property names](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer#Computed_property_names)

### String Methods

[String.prototype.includes()](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/String/includes)

### High-Order Functions

[High-Order Functions](https://en.wikipedia.org/wiki/Higher-order_function)

### Destructuring assignment

[Destructuring assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)

### Default parameters

[Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)

### Template Strings

[ES6 template strings](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals


### Fetch API

[Native Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)

Alternatives:

- [visionmedia/superagent](https://github.com/visionmedia/superagent)
- [mzabriskie/axios](https://github.com/mzabriskie/axios)

### Object.assign()

[Object.assign()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)

### Spread syntax

[Spread syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_operator)

### Modules

[ES6 export](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export)

[ES6 import](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)

## Referências