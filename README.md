## Sobre o projeto

Este projeto é uma aplicação frontend desenvolvida com React, utilizando o Create React App (CRA) como ambiente de desenvolvimento.

O objetivo principal é consolidar conceitos fundamentais do ecossistema React, com foco em boas práticas de desenvolvimento e estruturação de aplicações frontend.

## Tecnologias utilizadas
JavaScript (ES6+)
React
Node.js (ambiente de execução do build)
Webpack (bundler via CRA)
Babel (transpilação de JSX e ES6+)
ESLint (padronização de código)
HTML5
CSS3

---
## Como rodar o projeto
Dentro da pasta do seu projeto, instale as dependências:
```bash
npm install
```

Inicie o servidor de desenvolvimento:
```bash
npm start
```

Acesse no navegador: [http://localhost:3000](http://localhost:3000)

## Estrutura de pastas
```
meu-app/
├── public/        # index.html e arquivos estáticos
├── src/           # código fonte
│   ├── App.js     # componente principal
│   └── index.js   # ponto de entrada
└── package.json   # dependências e scripts
```

## Scripts disponíveis

| Comando | O que faz |
| `npm start` | Inicia o servidor de desenvolvimento |
| `npm run build` | Gera a versão de produção |
| `npm test` | Roda os testes |

---

## Extensoes utilizadas no VScode

VSCode
- EditorConfig
- ESLint
- Code Runner
- Prettier

Configuração do ESLint
```bash
npm i slint babel-eslint --save-dev
```
- depois disso, no terminal rode:
```bash
npx eslint --init
```

--> Code Runner
--> ESLint
---
# video aula:

Curso utilizado como base:
https://www.udemy.com/course/curso-de-javascript-moderno-do-basico-ao-avancado/learn/lecture/17170540#content


# exemplo de base do projeto
Projeto base do projessor, pra se espelhar em ecossistema:
https://github.com/luizomf/base-react-18-router-dom-v6-eslint-prettier
