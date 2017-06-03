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

## Referências