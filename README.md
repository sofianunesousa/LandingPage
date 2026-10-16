# 🎬 MovieCity — Landing Page

## 📌 Sobre o projeto

O **MovieCity** é uma landing page responsiva de um serviço de streaming fictício, desenvolvida com React e Vite. O projeto foi criado como um exercício prático para aprender a componentizar interfaces, utilizar CSS puro e adaptar layouts para diferentes tamanhos de tela.

A página apresenta um cabeçalho com navegação, um botão de login, uma área de apresentação e cards destinados a pôsteres de filmes.

## 🚀 Tecnologias utilizadas

- **React:** criação da interface por meio de componentes.
- **Vite:** ferramenta para criação e execução do projeto.
- **JavaScript:** desenvolvimento da lógica e das funcionalidades.
- **CSS3:** estilização, organização do layout e responsividade.
- **ESLint:** análise do código e identificação de possíveis problemas.

## ✨ Funcionalidades

- Cabeçalho com a logo MovieCity.
- Menu de navegação com as opções Filmes, Categoria, Sobre e Contato.
- Botão de Login.
- Menu hambúrguer para dispositivos móveis.
- Área principal com texto de apresentação e botão Mais.
- Grid com seis cards para exibição de pôsteres de filmes.
- Efeitos visuais ao passar o mouse sobre os cards.
- Layout responsivo para computadores, tablets e celulares.

## 📂 Estrutura do projeto

```text
01_landingpage/
├── public/
├── src/
│   ├── assets/
│   │   ├── afterlife.jpg
│   │   ├── transformers.jpg
│   │   ├── mowgli.jpg
│   │   ├── shift.png
│   │   ├── squidgame.webp
│   │   └── harrypotter.jpg
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Main.jsx
│   │   └── Home.jsx
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

*Observação: as imagens dos filmes devem ser adicionadas manualmente à pasta `src/assets/` para aparecerem nos cards.*

## ⚙️ Como executar o projeto

### Pré-requisitos

- Node.js instalado.
- npm instalado.
- Visual Studio Code ou outro editor de código.

### 1. Criar o projeto

```bash
npm create vite@latest 01_landingpage -- --template react
```

### 2. Entrar na pasta

```bash
cd 01_landingpage
```

### 3. Instalar as dependências

```bash
npm install
```

### 4. Executar o projeto

```bash
npm run dev
```

Após executar o comando, abra no navegador o endereço local apresentado pelo Vite, geralmente `http://localhost:5173/`.

## 📱 Responsividade

O layout utiliza Flexbox, CSS Grid e media queries para se adaptar a diferentes tamanhos de tela.

- **Até 1100px:** ajustes nos espaçamentos e nos tamanhos das fontes.
- **Até 900px:** colunas empilhadas e menu hambúrguer habilitado.
- **Até 600px:** cards organizados em duas colunas.
- **Até 380px:** ajustes adicionais para celulares pequenos.

## 🧪 Verificação do código

Para analisar o código com o ESLint, execute:

```bash
npm run lint
```

Para gerar a versão de produção, execute:

```bash
npm run build
```

## 🎯 Objetivo do exercício

Praticar o desenvolvimento de interfaces com React, a divisão de uma página em componentes reutilizáveis, a estilização com CSS puro e a criação de layouts responsivos.

## 👩‍💻 Considerações finais

O desenvolvimento do MovieCity permite colocar em prática conceitos fundamentais de desenvolvimento front-end, reforçando a organização do código, a reutilização de componentes e a adaptação de interfaces para diferentes dispositivos.
