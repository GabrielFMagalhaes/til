# NodeJS

NodeJS é uma plataforma que utiliza a linguagem Javascript.
> Foi construído em cima da V8 (Chrome) 


## NPM e YARN 

São gerenciadores de pacotes (para instalar bibliotecas de terceiros).
Também é possível disponibilizar novas bibliotecas.

> Yarn é mais rapido e mais atualizado. Além de ter compartilhamento por workspaces.


## Arquitetura Event-Loop

* Baseado em eventos
Execução de eventos e rotas na maioria das vezes.

* Call Stack
É uma pilha de funções (em loop) - LIFO

* Single Thread
Utilizando libs do C++ (libuv), é possível utilizar diversas threads


## Non-blocking I/O

1. Não é preciso retornar todos os dados em uma requisição 
2. Real-time application

> Muito utilizado em chats (WebSocket)


## FrameWorks 

 * Opinados
AdonisJS - Opinados
NestJS - Opinados

 * Não opinados
Express JS - Não opinados

> Frameworks opinadas diz respeito a sua estrutura muito bem definida