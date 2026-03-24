## Sobre o projeto

Este projeto é uma aplicação frontend desenvolvida com React utilizando o Create React App (CRA).

O objetivo é criar uma aplicação de lista de tarefas (To-Do List), com foco em aprendizado de conceitos fundamentais como:

* Componentização
* Estado (State)
* Manipulação de eventos
* Integração com APIs (futuro)

---
## Tecnologias utilizadas

* React v18.20.8
* JavaScript (ES6+)
* HTML5
* CSS3

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
|---|---|
| `npm start` | Inicia o servidor de desenvolvimento |
| `npm run build` | Gera a versão de produção |
| `npm test` | Roda os testes |

---

# Extensoes utilizadas no VScode

--> EditorConfig
- na raiz do projeto, clique com o botao direito e selecione a opcao 'generate .editorconfig/'
- em seguida, no terminal digite
```bash
npm i slint babel-eslint --save-dev
```
- depois disso, no terminal rode:
```bash
npx eslint --init
```

--> Code Runner
--> ESLint

