# Java Básico

Java é uma linguagem de programação orientada a objetos, amplamente utilizada para desenvolvimento de sistemas, aplicações web, aplicativos Android e sistemas corporativos.

## Variáveis

Variáveis são utilizadas para armazenar valores na memória.

### Exemplos

```java
String nome = "Marcos";
int idade = 20;
double altura = 1.75;
boolean estudante = true;
```

## Tipos Primitivos

* `byte` - números inteiros pequenos
* `short` - números inteiros de tamanho médio
* `int` - números inteiros
* `long` - números inteiros grandes
* `float` - números decimais de menor precisão
* `double` - números decimais de maior precisão
* `char` - caracteres
* `boolean` - valores verdadeiro ou falso

## Operadores Matemáticos

* `+` Soma
* `-` Subtração
* `*` Multiplicação
* `/` Divisão
* `%` Resto da divisão

### Exemplo

```java
int a = 10;
int b = 5;
int soma = a + b;
```

## Estruturas Condicionais

### If

Permite executar um bloco de código quando uma condição for verdadeira.

**Exemplo:**

Se a idade for maior ou igual a 18, exibir:

```text
Maior de idade
```

### If Else

Permite definir uma ação para verdadeiro e outra para falso.

**Exemplo:**

* Se a idade for maior ou igual a 18, exibir: `Maior de idade`
* Caso contrário, exibir: `Menor de idade`

### Switch

Utilizado quando existem várias opções possíveis.

**Exemplo:**

```text
1 - Cadastrar
2 - Listar
3 - Excluir
```

## Laços de Repetição

### For

Utilizado quando se sabe quantas vezes uma repetição ocorrerá.

### While

Utilizado quando não se sabe exatamente quantas repetições serão necessárias.

### Do While

Executa pelo menos uma vez antes de verificar a condição.

## Métodos

Métodos são blocos de código reutilizáveis.

### Exemplos

* Método para somar dois números
* Método para calcular média
* Método para exibir mensagens

## Entrada de Dados

A classe `Scanner` permite receber informações digitadas pelo usuário.

### Exemplos de Entrada

* Nome
* Idade
* Salário

## Saída de Dados

A saída de dados normalmente é realizada utilizando:

```java
System.out.println();
```

### Exemplos

* Exibir nome
* Exibir idade
* Exibir resultados de cálculos

## Boas Práticas

* Utilizar nomes descritivos para variáveis
* Evitar código duplicado
* Organizar o código em métodos
* Manter a indentação correta
* Utilizar comentários apenas quando necessário

## Exercícios

1. Criar um programa que exiba **"Olá Mundo"**
2. Criar um programa que receba nome e idade do usuário
3. Criar uma calculadora simples
4. Criar um programa que mostre os números de 1 a 100
5. Criar um programa que informe se um número é par ou ímpar
