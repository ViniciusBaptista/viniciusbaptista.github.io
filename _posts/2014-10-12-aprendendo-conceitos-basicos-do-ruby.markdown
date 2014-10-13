---
layout: post
title: "Aprendendo conceitos básicos do Ruby"
---

Olá galera, beleza?

A uma semana eu comecei a estudar um pouco sobre Ruby, pelo site do Codecademy.

Eu estava ansioso pra começar a aprender sobre Ruby, eu já tenho base no JS e queria aprender uma nova tecnologia.
Antes de aprender Ruby eu pensei em começar a aprender Python, mas acabei gostando mais de Ruby e ansioso pra estudar sobre.

Vou mostrar alguns códigos exemplos de Ruby que fiz nos exercícios do Codecademy.

O exemplo abaixo, o programa recebe entradas do usuário e no final todo o conteúdo digitado é formatado e mostrado.

``` ruby
print "What's your first name?"
first_name = gets.chomp
first_name.capitalize!
print "What's your last name?"
last_name = gets.chomp
last_name.capitalize!
print "What's your city?"
city = gets.chomp
city.capitalize!
print "What's your state or province?"
state = gets.chomp
state.upcase!

puts "Your name is #{first_name}, your last name is #{last_name}, your city is #{city} and your state or province is #{state}."
```
Neste exemplo abaixo, o programa lê um texto e mostra quantas vezes cada palava foi digitada!

``` ruby
puts "Text please: "
text = gets.chomp

words = text.split(" ")
frequencies = Hash.new(0)
words.each { |word| frequencies[word] += 1 }
frequencies = frequencies.sort_by {|a, b| b }
frequencies.reverse!
frequencies.each { |word, frequency| puts word + " " + frequency.to_s }
```

Assim que eu terminei o curso do Codecademy, eu comecei a fazer os exercícios existentes no site da PythonBrasil, como já tinha feito com JavaScript.

Usei os exercícios do site da PythonBrasil novamente para adquirir uma experiência no Ruby.

Aqui estão dois exercícios feitos em Ruby:

1º Exercício

``` ruby
# Faça um Programa que verifique se uma letra digitada é vogal ou consoante.

def verifique(letter)
  "aeiou".index(letter.downcase) ? "Vogal" : "Consoante"
end
```

2º Exercício

``` ruby
=begin
Classe Bola: Crie uma classe que modele uma bola:
Atributos: Cor, circunferência, material
Métodos: trocaCor e mostraCor
=end

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
Gosto muito de Javascript, mas o Ruby me impressionou bastante e estou entusiasmado pra aprender mais sobre essa linguagem.

