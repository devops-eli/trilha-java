# Introdução aos Tipos de Variáveis em Java

Java é uma linguagem de programação que exige a definição do tipo de dado que uma variável pode armazenar. Uma variável em Java é um espaço na memória onde podemos armazenar valores para serem utilizados durante a execução do programa. Cada variável em Java tem um tipo específico, o que ajuda a garantir que o programa manipule os dados de forma correta.

## Tipos de Variáveis em Java

Em Java, existem dois principais tipos de variáveis: **tipos primitivos** e **tipos de referência**.

### Tipos Primitivos
Os tipos primitivos são os tipos de dados básicos e fundamentais em Java. Eles são usados para representar valores simples, como números inteiros, números decimais, caracteres e valores lógicos.

#### Tipos Primitivos Comuns:
- **int**: Representa números inteiros (sem casas decimais), como `10`, `-5`, `1000`.
- **double**: Representa números com ponto flutuante, ou seja, números decimais, como `3.14`, `-0.99`.
- **char**: Representa um único caractere, como `'A'`, `'b'`, `'9'`.
- **boolean**: Representa valores lógicos, sendo `true` (verdadeiro) ou `false` (falso).

### Tipos de Referência
Os tipos de referência são usados para armazenar referências a objetos, como strings, arrays e objetos personalizados criados a partir de classes. Esses tipos de dados não armazenam o valor diretamente, mas sim a referência (ou endereço) do valor.

#### Exemplos de Tipos de Referência:
- **String**: Representa uma sequência de caracteres, como `"Olá, Mundo!"`.
- **Array**: Representa uma coleção de elementos do mesmo tipo, como `int[] numeros = {1, 2, 3, 4};`.

## Declaração de Variáveis

Em Java, para declarar uma variável, é necessário especificar o tipo de dado seguido pelo nome da variável. A declaração é feita da seguinte forma:

```java
tipo nome_da_variavel;