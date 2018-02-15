---
layout: post
title:  "1 - Programação em sequência"
excerpt: "Este capítulo visa ensinar uma técnica simples para começar o desenvolvimento do raciocínio lógico do aluno. O nome desta técnica é programação em sequência (entrada, processamento e saída de dados). Você irá desenvolver programas simples, mas funcionais, usando tipos diferentes de dados, variáveis e constantes, operadores e expressões aritméticas."
date:   2018-02-11 23:25:24 -0200
categories: [Lógica de programação]
---

>Este capítulo visa ensinar uma técnica simples para começar o desenvolvimento do raciocínio lógico do aluno. O nome desta técnica é programação em sequência (entrada, processamento e saída de dados). Você irá desenvolver programas simples, mas funcionais, usando tipos diferentes de dados, variáveis e constantes, operadores e expressões aritméticas.

### Etapas de ação de um computador

Os computadores no geral executam três funções básicas, sendo elas: entrada de dados, processamento dos dados e saída dos dados. 

- A função de **entrada de dados** é a parte onde o computador recebe algum dado do usuário e o guarda em sua memória para ser processado mais tarde, este dado pode ser um número ou um texto por exemplo.

- A função de **processamento dos dados** é a parte onde o computador vai usar os dados de entrada para realizar algum processamento, como um cálculo por exemplo.

- A função de **saída de dados** é a parte onde o computador exibe a informação processada para o usuário, como o resultado de um cálculo por exemplo.

Tendo estas funções em mente, um programa de computador, nada mais é do que um conjunto de instruções, dispostas de uma forma lógica e sequencial, afim de resolver executar uma ação e resolver um problema.

### Tipos de dados: primitivos ou dados básicos

Os dados são informações manipularas pelos seres humanos traduzidos para o computador. Eles são classificados em:

#### int (inteiro)
São os dados numéricos positivos ou negativos, que pertencem ao conjunto de números inteiros, excluindo qualquer valor numérico fracionário, por exemplo, o valores 3, 12, 100, -400, -1, entre outros.

{% highlight ruby %}
variavel = 10
{% endhighlight %}

#### float (real)
São os dados numéricos positivos ou negativos que pertencem ao conjunto dos números reais, incluindo todos os valores fracionários e inteiros, por exemplo, os valores -2.3, 50, 19.23, -1000, entre outros.

{% highlight ruby %}
variavel = -3.25
{% endhighlight %}

#### char ou string (caractere ou cadeia)
São caracteres delimitados pelo símbolo de aspas “ “. Eles são representados por letras (de A até Z), números (de 0 até 9), símbolos (qualquer um que possa ser escrito com o teclado de computador, por exemplo “&” ou “$”) ou palavra contendo estes símbolos. Por exemplo, os valores “texto”, “(11) 96123-2138”, “Rua 2, Apto. 311”, “77”, “ “ (espaço em branco), entre outros, são dados do tipo Char ou String. O dado do tipo Char, é usando quando se faz referência a um único caractere, por exemplo “A”. Já o dado do tipo String é usando quando estamos falando de um conjunto de caracteres delimitados por aspas, por exemplo, “palavra”.

{% highlight ruby %}
variavel_char = "a"
variavel_string = "Meu nome"
{% endhighlight %}

#### bool (lógico)
São os dados com valores binários do tipo sim ou não, verdadeiro ou falso, 0 ou 1, entre outros, em que apenas um dos valores pode ser escolhido.

{% highlight ruby %}
variavel = true
{% endhighlight %}
