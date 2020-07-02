# Testes automatizados

Utilizada para garantir o funcionamento da aplicação independente do número de novas funcionalidades e desenvolvedores no time.
> Não confundir com DDD


## Tipos de testes

1. Testes unitários

Testam funcionalidades específicas da aplicação (precisam ser funções puras).
> Funções puras não realizam chamada à uma API ou tem efeitos colaterais

2. Testes de integração

Testam uma funcionalidade completa, passando por várias camadas da aplicação, como por exemplo a criação de um usuário (como um usuário).
> Route -> Controller -> Serviço -> Repositório -> ...

3. Testes E2E

Testes que simulam ação do usuário dentro da aplicação (testes de interface)
> Clique no input de usuário -> Preencha 'gferreiram' -> Clique no input de senha -> ...


## TDD

TDD ou Test Driven Development é utilizado para criar testes antes de criar as funcionalidades da aplicação