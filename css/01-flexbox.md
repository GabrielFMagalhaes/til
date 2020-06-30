# Flexbox

Utilizado para estilização de componentes e construção de layouts responsivos.

Para começar a utiliza-lo, é necessário digitar o seguinte comando:
```
display: flex;
```
O comando acima alinham os itens (inicialmente) horizontalmente.


## Direções e Alinhamentos

Flex direction é utilizado para modificar alinhamento dos itens:
```
flex-direction: column;
```
Row para alinhamentos horizontais e Column para alinhamentos Verticais.

Alinhamentos são utilizados para posicionar itens na tela, verticalmente ou horizontalmente (muda de acordo com o flex direction).
```
align-items: flex-start;
justify-content: flex-start;
```

## Redimensionamento

Utilizado para caber todos os itens na tela ou redimensiona-los
```
flex-grow: 1;
flex-shrink: 1;
```
Ou, podemos utilizar somente o seguinte comando:
```
flex: 1;
```

## Wrap Itens

Utilizado para alinhar itens quando o seu tamanho maximo for ultrapassado (quebra de linha)
```
flex-wrap: wrap;
justify-content: space-between;
```

## Ordenação

Para efetivar uma melhoria do layout responsivo, podemos trocar as ordens em que um elemento é exibido em tela.
```
order: 1;
```