<div align="center">

# REACT
</div>


## Índice
- [1. PropTypes](#1-react-router-dom)
- [2. Lazy e Suspense](#2-lazy-e-suspense)
- [3. Memo](#3-memo)
- [4. useReducer](#4usereducer)
- [5. Classes](#5-classes)

### 1. PropTypes

__npm install prop-types__

O PropTypes irá retornar um erro caso o valor da propriedade passada seja um tipo de dado diferente do especificado. É também possível especificar se uma propriedade é obrigatória ou não.

### 2. Lazy e Suspense
Com o Lazy e Suspense podemos dividir o código da nossa aplicação. Assim o React só irá carregar certas partes do código, quando as mesmas forem necessárias.

### 3. Memo
Retorna um componente memorizado, evitando que o mesmo seja atualizado toda vez que o estado de um elemento pai mudar. Use apenas para elementos que não dependam de estados diferentes. (Não confundir com useMemo)

### 4. useReducer
O useReducer serve para lidarmos com estados que possuam funções fixas responsáveis por modificar o mesmo.

### 5. Classes
Antes dos hooks a única forma de criarmos componentes com estados reativos, era através da extensão da classe React.Component. O JSX que é renderizado pelo componente de classe deve estar dentro do retorno do método render().