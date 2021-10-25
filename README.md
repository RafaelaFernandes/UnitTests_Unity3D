# Unit tests on Unity 3D
> Project built for the grade C214 at INATEL using NUnit as main framework at Unity 3D

## Table of contents
* [General info](#general-info)
* [Test Runner](#test-runner)
* [Unity](#unity)
* [Presentation](#presentation)
* [Technologies](#technologies)

## General info
<img src="/doc/logo.png" />

O objetivo para o programa é realizar um Teste de Unidade com a linguagem escolhida ou sorteada em sala de aula.

O que é um teste de unidade?
Antes de mergulhar no código, é importante ter um conhecimento sólido do que é teste de unidade. Simplificando, um teste de unidade é um teste de alguma ação no software.

Um teste de unidade é (idealmente) para testar uma única “unidade” de código. Exatamente o que compõe uma "unidade" varia, mas o importante a se ter em mente é que um teste de unidade deve testar exatamente uma 'coisa' de cada vez.

Para escrever testes, você primeiro precisa saber sobre o executor de testes da Unity. O Test Runner permite que você execute testes e veja se eles passam. Para abrir o executor de teste do Unity, escolha Window ▸ General ▸ Test Runner.

<img src="/doc/teste.jpg" />

O que há em um pacote de teste?
Um teste de unidade é uma função que testa o comportamento de um pequeno conjunto de código específico. Como um teste de unidade é um método, ele precisa estar em um arquivo de classe para ser executado.

## Test Runner

O Test Runner percorrerá todos os seus arquivos de classe de teste e executará os testes de unidade neles. Um arquivo de classe que contém testes de unidade é chamado de suíte de testes.

Um conjunto de testes é onde você divide logicamente seus testes. Você deseja dividir seu código de teste entre diferentes suítes lógicas (por exemplo, uma suíte de testes para física e outra separada para combate). Para este tutorial, você só precisa de um conjunto de testes, então é hora de criá-lo. 

## Unity
Sobre o Unity:
O Unity 3D é um software que possibilita o desenvolvimento de jogos. Assim como toda game engine, ela facilita o desenvolvimento de jogos pelo fato de o desenvolvedor não precisar programar diretamente para DirectX ou OpenGL, pois ela já faz isso automaticamente.

Quais linguagens posso usar no Unity?
No programa Unity são utilizados diversos tipos de linguagem de programação, principalmente as linguagens C++ e C#, nos scripts dos objetos do jogo. Inclusive o phellype4 ja utilizou a linguagem java em alguns progrmas feitos no Unity. Ele permite também mesclar códigos, por exemplo, usar um código para andar em C# e outro código para pular em Java, assim por diante.

<img src="/doc/linguagens.jpg" />

Por que razão usar o Unity?
É que o Unity tem linguagem e interface mais amigáveis e fáceis de se utilizar, o que acaba atraindo mais programadores e desenvolvedores de games. ... Além disso, o Unity trabalha todos os seus games com o sistema de cenas, que, por sua vez, são compostas por game objects

## Presentation

Separamos a apresentação em duas partes:

1 - Introdução ao Unity (phellype4);

2 - Teste de Unidade (RafaelaFernandes).

	
## Technologies
Project is created with:
* Unity 2020.3.17f
* NUnity
* C#
