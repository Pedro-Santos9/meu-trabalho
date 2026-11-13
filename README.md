# GameZone - Loja Virtual de Jogos

Atividade Prática Avaliativa de React.js (Componentes, Props e Rotas).

## Como executar

```bash
npm install
npm run dev
```

Depois abra o endereço mostrado no terminal (normalmente http://localhost:5173).

## Estrutura

```
src/
├── components/  Header, Footer, Card, Menu, Button
├── pages/       Home, Produtos, Sobre, Contato, NotFound
├── data/        produtos.js (array de objetos dos jogos)
├── App.jsx      definição das rotas
├── main.jsx     ponto de entrada (BrowserRouter)
└── index.css    estilos
```

## Rotas

| Rota        | Conteúdo                                   |
|-------------|--------------------------------------------|
| `/`         | Página inicial                             |
| `/produtos` | Listagem de 6 jogos usando Cards           |
| `/sobre`    | Informações sobre a aplicação              |
| `/contato`  | Formulário (nome, e-mail e mensagem)       |
| `*`         | Página 404                                 |
