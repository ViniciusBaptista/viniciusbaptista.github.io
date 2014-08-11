---
layout: post
title: "Praticando com exercícios do Python Brasil"
---

Oi galera, tudo bem?

Como todos nós sabemos, sem praticar não aprendemos nada. E é sobre isso que irei falar.

A um mês atrás eu comecei a fazer alguns exercícios do site <a href='http://www.python.org.br/wiki/ListaDeExercicios'>Python Brasil</a>, são 9 seções de exercícios. 

Que você pode resolver em qualquer linguagem(Python, JavaScript, Ruby entre outras). Eu fiz os exercícios em JavaScript, por já ter um conhecimento básico da linguagem.

Vou mostrar alguns dos códigos mais simples, que consegui fazendo os exercícios. Você poderá ver todos que eu fiz no meu <a href='https://github.com/ViniciusBaptista/LearningJavascript/tree/master/python-brasil2'>Github</a>, visita lá. :)

Quinto exercício de Estrutura de Decisão:

``` javascript
/**
 * Faça um programa para a leitura de duas notas parciais de um aluno. 
 * O programa deve calcular a média alcançada por aluno e apresentar:
 * A mensagem "Aprovado", se a média alcançada for maior ou igual a 
 * sete;
 * A mensagem "Reprovado", se a média for menor do que sete;
 * A mensagem "Aprovado com Distinção", se a média for igual a dez
 */

function notas(nota1, nota2) {
  var media = (nota1 + nota2) / 2;

  switch (true) {
    case media >= 7 && media < 10:
      return 'Aprovado';
    case media < 7:
      return 'Reprovado';
    case media === 10:
      return 'Aprovado com Distinção';
    default:
      return 'Nota inválida';
  }
}

``` 

Nono exercício de Estrutura Sequencial:

``` javascript
/**
 * Faça um Programa que peça a temperatura em graus Fahrenheit, transforme 
 * e mostre a temperatura em graus Celsius.
 */

function transformacao(f) {
  return Math.round(5 * (f - 32) / 9) + ' °C'
}
```
Quinto exercício de Exercícios com Listas:

``` javascript
/**
 * Faça um Programa que leia 20 números inteiros e armazene-os num
 * vetor. Armazene os números pares no vetor PAR e os números IMPARES
 * no vetor impar. Imprima os três vetores.
 */

function vetor() {
  var numeros = [],
      par = [],
      impar = [];

  for (var i = 0; i < 20; i++) {
    arguments[i] % 2 === 0 ? par.push(arguments[i]) : impar.push(arguments[i]);
    numeros.push(arguments[i]);
  }

  return 'Números: '+ numeros +
         '\nPares: ' + par.join(', ') +
         '\nImpar: ' + impar.join(', ');
}

```

É isso galera, se quiserem ver mais das minhas soluções acessem meu Github, caso estejam interessados em resolverem esses exercícios, porém em linguagens diferentes,
acesse o site da Python Brasil. ;)

