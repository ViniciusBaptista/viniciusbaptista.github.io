---
layout: post
title: "Aprendendo um pouco de HTML e CSS"
---

Olá galera, beleza?

Semana passada comecei a aprender alguns fundamentos para desenvolver uma página web. 

Eu aprendi esses fundamentos no <a href="http://www.codecademy.com/">Codecademy</a>, um site bastante interessante para aqueles que querem aprender o básico sobre algumas linguagens de programação como: Ruby, Python e PHP.

Vou mostrar algumas das coisas que eu aprendi no Codecademy, vamos começar. :)

A primeira coisa que aprendi foi. Que é essencial no inicio do arquivo .html colocar o DOCTYPE, dessa maneira...

``` html
<!DOCTYPE html>
<!--Seu código html-->
```
É uma regra, sempre que começar a escrever algo em HTML você deve colocar o !DOCTYPE… para que o seu navegador saiba que o código que está sendo executado é um HTML.

Aprendi que o HTML tem uma estrutura a ser seguida, desta maneira:

``` html
<!DOCTYPE html>
<html>
  <head>
  </head>

  <body>
  </body>
</html>
```
Isso serve para organizar o seu código HTML e também para entender por exermplo, que tudo que há dentro da sua página fica entre as tags body(que significa: corpo), neste caso ‘Corpo da página’.

Outra coisa interessante que aprendi, montar listas ordenadas e não ordenadas:

Lista ordenada:

``` html
<!DOCTYPE html>
<html>
  <head>
    <title>Lista Ordenada</title>
  </head>
  <body>
    <!--Lista de afazeres pela manhã-->
    <ol>
      <li>Escovar os dentes</li>
      <li>Tomar café</li>
      <li>Fazer exercícios físicos</li>
    <ol>
  </body>
</html>
```
Lista não ordenada:

``` html
<!DOCTYPE html>
<html>
  <head>
    <title>Lista não ordenada</title>
  </head>
  <body>
    <!--Atividades diárias-->
    <ul>
      <li>Estudar HTML</li>
      <li>Estudar CSS</li>
      <li>Criar páginas, como exercício</li>
    </ul>
  </body>
</html>
```

Uma coisa bastante legal, foi trocar o tamanho, cor e estilo da fonte.

``` html
<!DOCTYPE html>
<html>
  <head>
    <title>Dando mais estilo a sua pagina</title>
  </head>
  <body>
    <h1 style="color: blue">Eu sou da cor azul! </h1>
    <p style="font-family: Arial">Olá, eu sou Arial!</p>
  </body>
</html>
```

E aprendi a usar CSS para fazer aquelas alterações de estilo de maneira mais prática.

``` css
h1 {
  color: blue;
}

p {
  font-family: Arial;
}
```
Bem mais prático, não é? Deixe seu código HTML mais bonito e mais limpo e ainda da estilo a sua página.

Para que esse código CSS funcione na sua página, você deve linkar o arquivo .css. Desta maneira:

``` html
<!DOCTYPE html>
<html>
  <head>
    <link type="text/css" rel="stylesheet" href="style.css">
    <!-- No href="" você deve colocar o caminho para a pasta aonde o arquivo está, mas se o seu código html estiver na mesma 
    pasta que o arquivo css, basta colocar o nome do arquivo -->
    <title>Dando mais estilo a sua pagina</title>
  </head>
  <body>
    <h1>Eu sou da cor azul! </h1>
    <p>Olá, eu sou Arial!</p>
  </body>
</html>
```

Por hoje é só pessoal, até a próxima!
