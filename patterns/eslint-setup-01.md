# ESLint

ESLint é extremamente importante para manter a padronização do projeto, ou seja, a forma dos desenvolvedores trabalharem em equipe.

O Node aceita finalização de códigos com ou sem ponto e vírgula, aceita aspas duplas ou simples. Desta forma, por ser um range alto de opções, a chance do projeto não estar totalmente alinhado em uma equipe, é grande.

O ESLint mantém a configuração do projeto, de maneira automatizada e simples.


## Instalação

Adicione o pacote para o ambiente de desenvolvimento:
```
yarn add eslint -D
```

Inicialize o arquivo
``` 
yarn eslint --init
```

Adicione as seguintes linhas, no Settings do VSCode:
```
	"[javascript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    },
    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.fixAll.eslint": true,
        }
    }
```

Quase tudo está padronizado agora, note que ao salvar, o ESLint se encarregará de fazer as correções necessárias. Entretanto, imports em TypeScript ainda são acusados como erros, sendo assim adicione a dependência:
```
yarn add -D eslint-import-resolver-typescript
```

Agora, no arquivo de configuração do eslint, adicione:
```
"rules": {
  "import/extensions": [
    "error",
    "ignorePackages",
    {
      "ts": "never"
    }
  ]
},

"settings": {
  "import/resolver": {
    "typescript": {}
  }
}
```

Para ignorar verificações em arquivos, crie um arquivo .eslintignore e adicione as extensões e pastas a serem ignoradas

Pronto, ao salvar as suas edições, o ESLint fará a padronização automaticamente 😊