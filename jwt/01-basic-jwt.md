# JWT

Traduzido para JSON Web Token, é um método de autenticação de sessões de usuários na Web.

## Token

São divididos em três partes:

* Headers

Definido os tipos do token, quais algoritmos foram utilizados.

* Payload

O token pode conter informações do usuário (não sensíveis), desta forma, podemos obter estes dados para utilizá-los posteriormente (como o ID).

* Assinatura

Garantia de que o token é restrito ao usuário que está utilizando.


## Instalação

Prepare algumas dependências de criptografia como 
```
yarn add bcryptjs
```

Posteriormente, prepare o token
```
yarn add jsonwebtoken
```

Também utilize middlewares para autenticações, para evitar que usuários não autorizados acessem rotas da aplicação.

