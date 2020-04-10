# Preparando o Projeto

Este arquivo é apenas uma base para inicializar o projeto com as configurações do Babel e do Webpack.

Inicialize a pasta do projeto
```
yarn init -y
```

Crie duas pastas: 'src' e 'public'
Posteriormente, instale o React DOM.
```
yarn add react react-dom
```


## Babel

Para configurar o Babel, adicione as suas dependências
```
yarn add @babel/core @babel/preset-env @babel/preset-react webpack-cli @babel/cli
```
E crie um arquivo 'babel.config.json'. Utilize as configurações do babeljs.io

Por fim, 'compile' a aplicação para um destino final
```
yarn babel src/index.js --out-file public/bundle.js
```


## Webpack

Para configurar o Webpack, adicione as suas dependências
```
yarn add webpack
```
E crie um arquivo 'webpack.config.js'.

Inicie o webpack
```
yarn webpack --mode development
```

Para evitar o restart constante do servidor, adicione a dependência e configure no 'webpack.config.js'
```
yarn add webpack-dev-server -D
```

Por fim, inicie com a seguinte linha de código
```
yarn webpack-dev-server --mode development
```