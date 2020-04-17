# Prettier
```
yarn add prettier eslint-config-prettier eslint-plugin-prettier -D
```

Adicione também os recomendações nas configurações do eslint
```
"extends": [
  "airbnb-base",
  "plugin:@typescript-eslint/recommended",
  "prettier/@typescript-eslint",
  "plugin:prettier/recommended"
],

"rules": {
  "prettier/prettier": "error",
},

"plugins": [
  "prettier"
]
```

Para evitar conflitos de regras com o eslint, crie um arquivo prettier.config.js e adicione as seguintes configurações
```
module.exports = {
  singleQuote: true,
  trailingComma: 'all',
  arrowParens: 'avoid',
};
```

Para ignorar verificações em arquivos, crie um arquivo .eslintignore e adicione as extensões e pastas a serem ignoradas