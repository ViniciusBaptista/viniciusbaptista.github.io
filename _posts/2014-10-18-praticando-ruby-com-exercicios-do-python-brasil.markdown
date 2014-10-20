---
layout: post
title: "Praticando Ruby com exercícios do Python Brasil"
---

Olá galera, beleza?

Como eu fiz com JavaScript, eu irei mostrar aqui alguns códigos que fiz usando os exercícios do Python Brasil, bom site para quem quer dar uma praticada em uma nova linguagem que acabou de aprender.

Neste post irei mostrar os mesmos códigos que fiz com JS para que vocês possam ver a diferença entre as duas linguagens. E mais 4 códigos das outras 4 secções de exercícios que eu fiz,  Vamos lá?

Lembrando que você poderá ver todos os exercícios que eu fiz no meu <a href="https://github.com/ViniciusBaptista/LearningRuby">Github</a>.

Estrutura de Decisão: Quinto Exercício

``` ruby
def notas(nota1, nota2)
  media = (nota1 + nota2) / 2

  case media
    when 7 .. 9 
      puts "Aprovado!"
    when 0 .. 6 
      puts "Reprovado!"
    when 10 
      puts "Aprovado com Distinção!"
    else  
    puts "Nota inválida!"
  end
end
```

Estrutura Sequencial: Nono Exercício

``` ruby
def transformacao(farenheit)
  (5 * (farenheit - 32) / 9)
end
```

Exercícios com Listas: Quinto Exercício

``` ruby
def vetor(*numbers)
  par = []
  impar = []
  
  if numbers.length < 20 || numbers.length > 20
    return "Digite 20 números!"
  end

  numbers.each { |j| 
    if j % 1 != 0
      return "Digite apenas números inteiros!"
    end
  }

  numbers.each { |n| n % 2 == 0 ? par.push(n) : impar.push(n)}

  "Números digitados: #{numbers} \nNúmeros pares: #{par} \nNúmeros impares: #{impar}"
end
```
Estrutura de Decisão: Décimo Sétimo Exercício

``` ruby
def bissexto(ano)
  puts ano % 400 == 0 || (ano % 4 == 0 && ano % 100 != 0)
end
```

Exercícios Classes: Prímeiro Exercício

``` ruby
class Bola
  def initialize(cor, circunferencia, material)
    @cor = cor
    @circunferencia = circunferencia
    @material = material
  end

  def troca_cor(cor)
    @cor = cor
  end

  def mostra_cor
    puts @cor
  end
end
```

Exercícios com Strings: Prímeiro Exercício

``` ruby
def comparacao(str1, str2)
  puts "String1: #{str1}\nString2: #{str2}"
  puts "Tamanho de '#{str1}': #{str1.length}\nTamanho de '#{str2}': #{str2.length}"

  if str1 != str2 
    print "As duas strings são de tamanhos diferentes. \nAs duas strings possuem conteúdo diferente." 
  elsif str1 == str2
    print "As duas strings possuem o mesmo conteúdo."
  end
end
```
Exercícios com Funções: Décimo Segundo Exercício

``` ruby
def shuffle(text)
  text
    .split("")
    .shuffle
    .join("")
end
```

É isso galera, quem quiser olhar mais exercícios resolvidos só dar uma olhada no meu Github!