## 📚 Curso de JavaScript — Full Course for Beginners

Curso de introdução ao **JavaScript** realizado como parte dos meus estudos em programação.

## 🎓 Sobre o curso

- 🎓 **Curso:** Learn JavaScript - Full Course for Beginners
- ▶️ **Plataforma:** YouTube
- 📺 **Canal:** freeCodeCamp.org
- 🌱 **Nível:** Iniciante
- ⏱️ **Duração:** aproximadamente 3h26min
- 📚 **Conteúdo:** 134 partes

## 🔗 Acessar o curso

[▶️ Acessar o curso no YouTube](https://www.youtube.com/watch?v=PkZNo7MFNFg)

---

O curso apresenta os principais fundamentos da linguagem **JavaScript**, começando pelos conceitos básicos e avançando para recursos do **ES6**.
## 📖 Conteúdos estudados

### 🟨 Fundamentos do JavaScript

- Execução de JavaScript
- Comentários no código
- Declaração e inicialização de variáveis
- `var`, `let` e `const`
- Atribuição de valores
- Case sensitivity
- Tipos de valores
- Operadores matemáticos
- Incremento e decremento
- Números decimais
- Resto da divisão (`%`)
- Operadores de atribuição

### 🔤 Strings

- Declaração de strings
- Aspas simples e duplas
- Caracteres de escape
- Concatenação
- Operador `+`
- Operador `+=`
- Interpolação de variáveis
- Propriedade `.length`
- Bracket notation
- Imutabilidade das strings

### 📦 Arrays

- Criação de arrays
- Acesso aos elementos
- Alteração de valores
- Arrays multidimensionais
- Arrays aninhados
- `push()`
- `pop()`
- `shift()`
- `unshift()`

### ⚙️ Funções

- Criação de funções
- Parâmetros e argumentos
- Retorno de valores com `return`
- Valores `undefined`
- Escopo global
- Escopo local
- Diferença entre variáveis globais e locais
- Funções reutilizáveis

### 🔀 Condicionais

- Valores booleanos (`true` e `false`)
- `if`
- `else`
- `else if`
- Operadores de igualdade
- Operadores lógicos `&&` e `||`
- Ordem das condições
- Encadeamento de condições
- `switch`

### 🏗️ Objetos

- Criação de objetos
- Propriedades
- Dot notation
- Bracket notation
- Atualização de propriedades
- Adição de propriedades
- Remoção de propriedades
- Objetos para consultas
- Objetos aninhados
- Arrays dentro de objetos
- Manipulação de objetos complexos

### 🔁 Loops

- `while`
- `for`
- `do...while`
- Iteração sobre arrays
- Loops aninhados
- Contagem crescente
- Contagem regressiva
- Números ímpares

### 🎲 Outros conceitos

- Números aleatórios
- `Math.random()`
- `parseInt()`
- Operador ternário
- Operador ternário múltiplo

---
🚀 ES6

Durante a parte final do curso, também foram apresentados recursos introduzidos no ES6 (ECMAScript 2015):

- Diferenças entre "var", "let" e "const"
- Arrow Functions
- Parâmetros padrão
- Rest Operator ("...")
- Spread Operator ("...")
- Destructuring Assignment
- Template Literals
- Simple Fields
- Declarative Functions
- Classes
- Getters e Setters
- "import" e "export"

---
1. 🟨 Introdução

O que é JavaScript?

JavaScript é uma linguagem de programação utilizada principalmente para adicionar interatividade e comportamento dinâmico às páginas e aplicações.

Na Web, normalmente encontramos:

- HTML → estrutura da página.
- CSS → aparência e estilo.
- JavaScript → comportamento e interatividade.

Exemplo:

console.log("Olá, mundo!");

"console.log()" permite mostrar uma informação no console do navegador ou do ambiente em que o JavaScript está sendo executado.

---

2. ▶️ Executando JavaScript

O JavaScript pode ser executado diretamente no navegador ou através de ambientes como o Node.js.

Em uma página HTML, podemos utilizar:

<script>
    console.log("Olá!");
</script>

Também podemos colocar o JavaScript em um arquivo separado:

<script src="script.js"></script>

Nesse caso, o código fica no arquivo:

script.js

---

3. 💬 Comentários

Comentários são textos escritos dentro do código que não são executados pelo JavaScript.

Eles servem para explicar o código ou fazer anotações.

Comentário de uma linha

// Isso é um comentário

Tudo depois de "//" naquela linha é ignorado.

Comentário de várias linhas

/*
    Este comentário
    possui várias linhas.
*/

Comentários ajudam na organização e manutenção do código.

---

4. 📦 Variáveis

O que é uma variável?

Uma variável é um espaço utilizado para armazenar um valor que pode ser utilizado posteriormente.

let nome = "Emilly";

Nesse exemplo:

- "let" → palavra-chave usada para declarar a variável.
- "nome" → nome da variável.
- "=" → operador de atribuição.
- ""Emilly"" → valor armazenado.

Podemos imaginar:

nome → "Emilly"

---

Declarar uma variável

Declarar significa informar ao JavaScript que queremos criar uma variável.

let idade;

Nesse momento, a variável existe, mas ainda não recebeu um valor.

---

Atribuir um valor

Atribuir significa colocar um valor dentro da variável.

idade = 20;

Agora:

idade → 20

Também podemos fazer as duas coisas de uma vez:

let idade = 20;

---

Variável não inicializada

Uma variável declarada sem valor possui o valor:

undefined

Exemplo:

let nome;

console.log(nome);

Resultado:

undefined

---

Case Sensitive

JavaScript diferencia letras maiúsculas e minúsculas.

let nome = "Emilly";
let Nome = "Maria";

São duas variáveis diferentes.

nome
Nome

---

5. ➕ Operadores matemáticos

JavaScript permite realizar operações matemáticas.

Adição

5 + 3

Resultado:

8

Subtração

5 - 3

Resultado:

2

Multiplicação

5 * 3

Resultado:

15

Divisão

10 / 2

Resultado:

5

Resto da divisão

O operador "%" retorna o resto de uma divisão.

10 % 3

Resultado:

1

Isso é chamado de módulo ou operador de resto.

---

Incremento

Para aumentar um número em 1:

let numero = 5;

numero++;

Agora:

numero = 6

Também podemos usar:

numero = numero + 1;

---

Decremento

Para diminuir um número em 1:

let numero = 5;

numero--;

Agora:

numero = 4

---

Números decimais

JavaScript também trabalha com números decimais:

let numero = 10.5;

Podemos realizar operações:

let resultado = 2.5 * 4;

---

Operadores de atribuição

Podemos combinar operações matemáticas com atribuição.

Em vez de:

numero = numero + 5;

podemos escrever:

numero += 5;

Outros exemplos:

numero -= 5;
numero *= 5;
numero /= 5;

---

6. 🔤 Strings

O que é uma String?

Uma String representa uma sequência de caracteres, normalmente utilizada para armazenar textos.

let nome = "Emilly";

Também podemos utilizar aspas simples:

let nome = 'Emilly';

---

Aspas dentro de Strings

Se precisamos colocar aspas dentro de um texto, podemos utilizar o caractere de escape "\".

let frase = "Ela disse: \"Olá!\"";

O "\" informa que a próxima aspa deve ser interpretada como parte do texto.

---

Caracteres de escape

Alguns caracteres especiais:

Escape| Significado
"\'"| Aspas simples
"\""| Aspas duplas
"\\"| Barra invertida
"\n"| Nova linha
"\t"| Tabulação

Exemplo:

console.log("Olá\nMundo");

Resultado:

Olá
Mundo

---

Concatenação

Concatenação significa juntar Strings.

Utilizamos o operador "+":

let nome = "Emilly";

let mensagem = "Olá, " + nome;

Resultado:

Olá, Emilly

---

Operador "+="

Também podemos adicionar conteúdo ao final de uma String:

let texto = "Olá";

texto += " Emilly";

Resultado:

Olá Emilly

---

Tamanho de uma String

A propriedade ".length" informa quantos caracteres existem.

let nome = "Emilly";

console.log(nome.length);

O resultado será:

6

O espaço também conta como caractere.

---

Bracket Notation

Podemos acessar um caractere específico utilizando colchetes:

let nome = "Emilly";

console.log(nome[0]);

Resultado:

E

A contagem começa em 0.

E m i l l y
0 1 2 3 4 5

Portanto:

nome[0] // E
nome[1] // m
nome[2] // i

---
Imutabilidade das Strings

Strings são imutáveis.

Isso significa que não podemos alterar diretamente um caractere:

let nome = "Emilly";

nome[0] = "A";

Isso não modifica a String original.

Para alterar, precisamos criar uma nova String.

---

7. 📚 Arrays

O que é um Array?

Um Array é uma estrutura utilizada para armazenar vários valores dentro de uma única variável.

let frutas = ["maçã", "banana", "uva"];

Cada elemento possui uma posição chamada índice.

maçã     banana     uva
 0          1         2

---

Acessando valores

console.log(frutas[0]);

Resultado:

maçã

---

Alterando valores

frutas[1] = "laranja";

Agora:

["maçã", "laranja", "uva"]

---

Arrays aninhados

Podemos colocar arrays dentro de outros arrays.

let lista = [
    ["maçã", "banana"],
    ["carro", "moto"]
];

Isso é chamado de array multidimensional ou array aninhado.

Para acessar:

lista[0][1];

Resultado:

banana

---

"push()"

Adiciona um elemento ao final do array.

let frutas = ["maçã", "banana"];

frutas.push("uva");

Resultado:

["maçã", "banana", "uva"]

---

"pop()"

Remove o último elemento.

frutas.pop();

---

"shift()"

Remove o primeiro elemento.

frutas.shift();

---

"unshift()"

Adiciona um elemento no início.

frutas.unshift("laranja");

---
