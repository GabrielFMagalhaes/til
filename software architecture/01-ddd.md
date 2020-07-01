# DDD

DDD ou Domain Driven Design é uma metodologia com boas praticas para desenvolvimento de projetos
> Não confundir com TDD


## DDD ou TDD 

DDD é utilizado como patternas (ou boas praticas) para desenvolvimento de projetos (voltado apenas para o Backend)

TDD (Test Driven Development) é uma metodologia para criar testes antes de criar funcionalidades (podendo ser utilizada tanto para Frontend quanto para Backend).


## Camada de Infra

Como a aplicação será integrada com as funcionalidades escolhidas (Express, Frameworks, ORMs, entre outros).


## Camada de Domínio

São aplicadas as regras de negócio das funcionalidades do projeto.


## SOLID

* Single Responsability Principle
Uma classe deve ter somente um único motivo para ser modificada (logo, deve ter uma única responsabilidade)

* Liskov Substitution Principle
Dita boas praticas para isolamento das camadas de integrações do projeto. 
> Um service não deve saber se os dados são persistidos em um MySQL

* Dependency Inversion Principle
Devemos depender de abstrações e não das implementações

* Dependency Inversion 