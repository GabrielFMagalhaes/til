# TypeORM

Utilizado para gerenciar relacionamento de objetos.

Instale a dependência do TypeORM
```
yarn add typeorm pg
```

Configure o arquivo ormconfig.js com os parâmetros de conexão
Lembre-se de consultar a documentação do [TypeORM](https://typeorm.io/#/)


## Tabelas

Para criar arquivos para novas tabelas, utilize comandos como:
```
yarn typeorm migration:create -n NomeTabelaFuncao
```

Lembre-se que o migrations funciona como um controle de versão das suas tabelas criadas. Desta forma, a cada nova atualização, crie uma migration diferente: CreateUser, AddColumNameUser, UpdateUser



