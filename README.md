_Repositório apenas para estudo_

# SOLID - Teoria e Prática

Desenvolvido com base no vídeo do [Eduardo Pires](https://www.youtube.com/watch?v=Q2QdkiX6p_Y)

Instrutor:

- [Eduardo Pires](https://www.eduardopires.net.br/)

Referências:

- https://www.eduardopires.net.br/2015/01/solid-teoria-e-pratica/
- https://www.eduardopires.net.br/2013/04/orientacao-a-objeto-solid/

# Teórico

## Princípios SOLID

SOLID é o acrônimo dos cinco primeiros princípios da programação orientada a objetos e design de código identificados por Robert C. Margin (ou Uncle Bob) por volta do ano 2020

Os princípios SOLID devem ser aplicados para obter os benefícios da orientação a objetos, tais como:

- Seja fácil de se manter, adaptar e se ajustar as alterações do escopo;
- Seja testável e de fácil entendimento;
- Seja extensível para alterações com o menor esforço necessário;
- Que forneça o máximo de reaproveitamento;
- Que permaneça o máximo de tempo possível em utilização

Utilizando os princípios SOLID é possível evitar muitos problemas comuns

- Dificuldade na testabilidade / criação de testes de unidade;
- Código macarrônico, sem estrutura ou padrão;
- Dificuldades de isolar funcionalidades;
- Duplicação de código, uma alteração precisa ser feita em N pontos;
- Fragilidade, o código quebra facilmente sem vários pontos após alguma mudança.

<br>

## SRP - Single Responsability Principle

"A class should have one, and only one, reason to change“

Uma classe deve ter um, e apenas um, motivo para ser modificada

<br>

## OCP – Open Closed Principle

“Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification.”

“Entidades de software (classes, módulos, funções, etc) devem estar abertas para extensão, mas fechadas para modificação.”

<br>

## LSP- Liskov Substitution Principle

“Let q(x) be a property provable about objects x of type T. Then q(y) should be provable for objects y of type S, where S is a subtype of T.”

“Se q(x) é uma propriedade demonstrável dos objetos x de tipo T. Então q(y) deve ser verdadeiro para objetos y de tipo S onde S é um subtipo de T.” “Uma classe base deve poder ser substituída pela sua classe derivada.” Se nada como um pato, voa como um pato, porém precisa de baterias, provavelmente você possui um problema de abstração

<br>

## - ISP - Interface Segregation Principle

“States that no client should be forced to depend on methods it does not use “

“Clientes não devem ser forçados a depender de métodos que não usam.” Muitas interfaces específicas são melhores do que uma interface única.

<br>

## - DIP - Dependency Inversion Principle

"High-level modules should not depend on low-level modules. Both should depend on abstractions. Abstractions should not depend on details. Details should depend on abstractions. “

“Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender de abstrações; Abstrações não devem depender de detalhes. Detalhes devem depender de abstrações.” Dependa de uma abstração e não de uma implementação.
