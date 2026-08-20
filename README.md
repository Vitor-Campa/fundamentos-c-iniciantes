# fundamentos-c-iniciantes
Miniguia de estudos sobre os fundamentos da linguagem C utilizando o NotebookLM.
# Fundamentos da Linguagem C para Iniciantes

## 1. Contexto e Objetivos

O objetivo deste projeto é estudar os fundamentos da linguagem C utilizando o NotebookLM como ferramenta de aprendizagem.

O foco será compreender os principais conceitos de C de forma simples, como variáveis, operadores, entrada e saída de dados, condições e estruturas de repetição.


## 2. Tema Escolhido

**Fundamentos da Linguagem C para Iniciantes**

A linguagem C é utilizada para desenvolver diversos tipos de programas e permite aprender conceitos importantes de programação.


## 3. Fontes Utilizadas

Foram utilizadas de 3 a 5 fontes sobre a linguagem C e seus conceitos básicos.

* Fonte 1: **Estruturas Condicionais** – (https://sites.icmc.usp.br/andretta/ensino/aulas/sme0230-1-17/aula3-condicionais.pdf)
* Fonte 2: **apostila.dvi** – (https://www.ime.usp.br/~yoshi/2014ii/mac115/Apostila/apostila.pdf)
* Fonte 3: **Programação de Computadores I Aula 08 Programação: Estruturas de Repetição** – (http://www.decom.ufop.br/romildo/cea030.2011-1/slides/08-estruturas-de-repeticao.pdf)


## 4. Engenharia de Prompts

Foram utilizados prompts para facilitar o aprendizado:

> Explique o que é a linguagem C para uma pessoa que está começando a programar.

> Explique variáveis, tipos de dados e operadores em C utilizando exemplos simples.

> Explique if, else, for, while e do while para iniciantes.

> Com base nas fontes, crie um resumo dos principais conceitos da linguagem C.


## 5. Cicatrizes e Troubleshooting

Algumas respostas apresentaram conceitos mais avançados do que o necessário, como ponteiros, matrizes e `struct`.

Para melhorar os resultados, os prompts foram modificados para pedir explicações mais simples e voltadas para iniciantes.


# 6. Miniguia de Estudos

## 6.1 O que é C?

C é uma linguagem de programação utilizada para desenvolver diferentes tipos de programas e sistemas.


## 6.2 Variáveis e Tipos de Dados

Variáveis armazenam informações utilizadas pelo programa.

* `int` → números inteiros.
* `float` → números decimais.
* `char` → caracteres.

Exemplo:

```c
int idade = 20;
float altura = 1.75;
char letra = 'A';
```


## 6.3 Operadores

Os principais operadores são:

* `+` → soma
* `-` → subtração
* `*` → multiplicação
* `/` → divisão
* `%` → resto da divisão
* `==` → igual
* `!=` → diferente
* `>` → maior
* `<` → menor

## 6.4 Entrada e Saída

`printf()` mostra informações na tela.

`scanf()` recebe dados do usuário.

`fgets()` pode ser utilizado para receber textos.


## 6.5 Condições

`if` verifica uma condição e `else` é utilizado quando essa condição é falsa.

```c
if (idade >= 18)
{
    printf("Maior de idade");
}
else
{
    printf("Menor de idade");
}
```


## 6.6 Repetições

* `for` → utilizado quando sabemos a quantidade de repetições.
* `while` → repete enquanto uma condição for verdadeira.
* `do while` → executa primeiro e verifica a condição depois.


# 7. Glossário

* **Variável:** armazena um valor.
* **`int`:** número inteiro.
* **`float`:** número decimal.
* **`char`:** caractere.
* **`if`:** verifica uma condição.
* **`else`:** executa quando a condição é falsa.
* **`for`:** estrutura de repetição.
* **`while`:** repete enquanto uma condição for verdadeira.
* **`printf()`:** mostra informações na tela.
* **`scanf()`:** recebe informações do usuário.
* **`fgets()`:** lê textos.


# 8. Prompts Reutilizáveis

> Explique [CONCEITO] em C de forma simples para um iniciante.

> Crie exercícios fáceis sobre [CONCEITO] em C.

> Explique este código C linha por linha.

> Encontre o erro neste código C e explique como corrigi-lo.

> Compare [CONCEITO 1] e [CONCEITO 2] em C.


# 9. Conclusão

O uso do NotebookLM ajudou a organizar o estudo da linguagem C e compreender seus principais conceitos.

Também foi possível perceber que prompts mais específicos produzem respostas mais adequadas ao objetivo do estudo.

O resultado final é um pequeno guia de consulta para quem está começando a aprender programação em C.
