---
layout: post
title: "Aprendendo conceitos básicos de CSS"
---

Oi pessoal, beleza?

Esse post é a continuação do <a href='http://viniciusbaptista.github.io/2014/08/03/aprendendo-um-pouco-de-html-e-css.html'>Aprendendo um pouco de HTML e CSS</a>, porém agora falando um pouco mais sobre os conceitos básicos do CSS.

Primeiro vamos a definição de CSS:

“CSS é a cigla para: Cascading Style Sheets.
O CSS é a linguagem usada para descrever a aparência e a formatação do seu arquivo HTML.”

Dito isso irei mostrar algumas coisas que aprendi, vamos começar?

Sempre que você estiver trabalhando com um arquivo CSS no seu projeto, você deve colocar um link desse arquivo no seu HTML, para que esse código funcione corretamente. 
Irei demonstrar:

``` html
<!DOCTYPE html>
<html>
  <head>
    <!--Aqui está o link-->
    <link type="text/css" rel="stylesheet" href="style.css">
    <title>CSS</title>
  </head>
  
  <body>
    <!--Seu código aqui-->
  </body>
</html>
```

O CSS como qualquer outra linguagem de programação tem sua sintaxe. E particularmente achei a sintaxe muito simples e pratica, vou mostrar:

```css
selector {
  property: value;
}
```
No lugar do ‘selector’ você deve colocar o que deve ser formatado no seu html. Por exemplo: eu quero que todas as tag’s 'p', sejam da cor vermelha.

``` css
p {
  color: red;
}
```
O legal do CSS é que você pode colocar várias propriedades dentro de um seletor, assim:

```css
p {
  color: red;
  font-family: Arial;
  font-size: 20px;
}
```
Uma coisa bem importante, no final de toda a propriedade dentro do CSS você deve colocar ponto e vírgula. Para que o CSS saiba que você terminou de fazer uma propriedade e está pronto para fazer outra.

``` css
p {
  font-family: Arial; /*<= O ponto e virgula para representar o final da sua propriedade.*/
  font-size: 21;
}
```
E é isso galera, um pouco do que eu aprendi no <a href='http://www.codecademy.com/'>Codecademy</a>.

Abraços, até a próxima. 
