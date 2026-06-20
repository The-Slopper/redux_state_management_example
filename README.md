# Store de Usuários (Redux)

Gerência de estado de usuários com Redux em uma aplicação React.

## Metadados

| Campo | Valor |
|-------|-------|
| Linguagem | JavaScript |
| Biblioteca | Redux + React-Redux |
| Versão | 1.0.0 |
| Licença | MIT |
| Responsável | Equipe de Frontend |

## Descrição

Define o store, o reducer e as ações para listar, adicionar, incrementar um contador e limpar
a lista de usuários, além de um componente de exemplo que lê o estado.

## Estrutura

```
frontend/redux/
└── src/store.js
```

## Uso

```js
import { store, adicionarUsuario, buscarUsuarios } from './src/store';
```
