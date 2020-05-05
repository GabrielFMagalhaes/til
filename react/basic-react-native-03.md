# React

É uma versão do React para desenvolvimento mobile (multiplataforma).
Também é uma interface web convertida pra uma interface nativa.


## Arquitetura

Utilizado o JSX do Javascript passa por um packager (Metro Bundler) que monitora códigos para gerar um Bundle JS. O Bundle por sua vez é passado por uma Bridge para gerar um app Android ou iOS.


## Expo

SDK com um conjunto de funcionalidades prontas, como câmeras, videos, integrações de API etc.
Completamente emulável pelo app no celular.
O Expo tem limitação sobre o controle do código nativo. Além de diversas bibliotecas não terem suporte.

## Iniciando o projeto

Primeiramente, instale o React-Native e prepare o projeto:
```
npx react-native init appgobarber --template react-native-template-typescript
```

Para iniciar o projeto, será necessário fazer uso de emuladores ou dispositivos físicos.