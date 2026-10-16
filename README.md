# 🎬 MovieCity

### Seu próximo filme favorito está aqui.

O **MovieCity** é uma landing page responsiva inspirada em plataformas de streaming, desenvolvida com React e Vite. O projeto apresenta uma seleção de filmes em uma interface visual moderna, com navegação adaptável para computadores, tablets e dispositivos móveis.

A aplicação foi criada com foco na prática de desenvolvimento front-end, componentização, organização de código e construção de layouts utilizando CSS puro.

---

## 🖥️ Visão geral

**Principais características**

- 🎞️ Catálogo visual com cards de filmes.
- 🧭 Cabeçalho com navegação entre seções.
- 🔐 Botão de acesso à área de login.
- 📱 Layout adaptável a diferentes resoluções.
- ☰ Menu hambúrguer para dispositivos menores.
- 🎨 Estilização personalizada com CSS.
- ⚛️ Interface construída com componentes React.

### 📸 Prévia do projeto

Adicione abaixo as capturas de tela da aplicação:

<!-- Substitua os caminhos pelas imagens reais do projeto. -->

| Desktop | Tablet | Mobile |
|:---:|:---:|:---:|
| Adicione uma imagem | Adicione uma imagem | Adicione uma imagem |

---

## 🛠️ Tecnologias

| Tecnologia | Aplicação no projeto |
|---|---|
| React 19 | Construção da interface por componentes |
| Vite 7 | Ambiente de desenvolvimento e build |
| JavaScript | Lógica e funcionalidades da aplicação |
| CSS3 | Estilização, layouts e responsividade |
| ESLint | Análise e padronização do código |
| HTML5 | Estrutura principal da página |

O projeto utiliza CSS puro, sem frameworks de estilização, para reforçar o aprendizado de Flexbox, CSS Grid, media queries e organização dos estilos.

---

## 📋 Requisitos para execução

Antes de iniciar, você precisará de:

- Node.js compatível com a versão do Vite utilizada.
- npm, instalado junto com o Node.js.
- Visual Studio Code ou outro editor de sua preferência.
- Navegador atualizado.

Verifique as versões instaladas:

```bash
node -v
npm -v
```

---

## 🚀 Instalação e execução

Siga as etapas abaixo para executar o MovieCity localmente.

**1. Clone o repositório**

```bash
git clone URL_DO_SEU_REPOSITORIO
```

**2. Entre na pasta do projeto**

```bash
cd MovieCity
```

Ajuste o caminho caso o projeto esteja em uma subpasta.

**3. Instale as dependências**

```bash
npm install
```

**4. Inicie o servidor de desenvolvimento**

```bash
npm run dev
```

**5. Acesse a aplicação**

Abra no navegador o endereço informado pelo Vite, normalmente:

`http://localhost:5173`

As alterações salvas nos arquivos são refletidas automaticamente durante o desenvolvimento.

---

## 📂 Organização do projeto

```text
MovieCity/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── imagens dos filmes
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Main.jsx
│   │   └── Home.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── eslint.config.js
├── package.json
├── package-lock.json
└── vite.config.js
```

*Observação: a estrutura acima representa a organização descrita para o projeto. Os arquivos e as pastas devem corresponder à versão atual do repositório.*

---

## ⚙️ Arquitetura da aplicação

A interface é dividida em componentes com responsabilidades específicas:

- **`main.jsx`** — inicializa a aplicação React.
- **`App.jsx`** — componente principal da aplicação.
- **`Home.jsx`** — organiza os componentes da página inicial.
- **`Header.jsx`** — contém a identidade visual e a navegação.
- **`Main.jsx`** — apresenta o conteúdo principal e os cards de filmes.
- **`index.css`** — concentra os estilos globais e as regras responsivas.

### Fluxo de renderização

```text
index.html
    │
    ▼
main.jsx
    │
    ▼
App.jsx
    │
    ▼
Home.jsx
    ├── Header.jsx
    └── Main.jsx
```

Essa divisão facilita a manutenção, a reutilização de componentes e a evolução da interface.

---

## 📱 Design responsivo

O MovieCity adapta sua estrutura de acordo com o tamanho da tela.

| Resolução | Comportamento |
|---|---|
| Acima de 1100px | Layout amplo para desktops |
| Até 1100px | Ajustes de espaçamento e tipografia |
| Até 900px | Conteúdo reorganizado e menu compacto |
| Até 600px | Cards distribuídos em duas colunas |
| Até 380px | Ajustes para telas menores |

### Recursos de responsividade

- Flexbox para alinhamento e distribuição de elementos.
- CSS Grid para organização do catálogo.
- Media queries para adaptação dos componentes.
- Unidades flexíveis para evitar estouro de conteúdo.
- Menu hambúrguer para facilitar a navegação em telas menores.

---

## 🧪 Verificação e build

O projeto disponibiliza comandos para validar o código e gerar uma versão de produção.

| Comando | Finalidade |
|---|---|
| `npm run dev` | Inicia o ambiente de desenvolvimento |
| `npm run lint` | Analisa o código com ESLint |
| `npm run build` | Gera os arquivos de produção |
| `npm run preview` | Permite visualizar a versão compilada localmente |

Para verificar a aplicação antes da publicação:

```bash
npm run lint
npm run build
npm run preview
```

Após o build, os arquivos otimizados são gerados na pasta `dist/`.

---

## 🔮 Melhorias futuras

O MovieCity pode evoluir com a implementação de novos recursos:

- [ ] Integrar uma API de filmes, como a TMDB.
- [ ] Exibir sinopses, gêneros, avaliações e datas de lançamento.
- [ ] Criar páginas individuais para os filmes.
- [ ] Implementar pesquisa e filtros por categoria.
- [ ] Adicionar um sistema funcional de autenticação.
- [ ] Criar listas de favoritos.
- [ ] Desenvolver um carrossel de filmes.
- [ ] Melhorar a navegação por teclado e os recursos de acessibilidade.
- [ ] Publicar a aplicação para acesso online.

As funcionalidades listadas são sugestões de evolução e não representam necessariamente recursos já implementados.

---

## 🎯 Objetivo de aprendizagem

Este projeto tem como objetivo consolidar conhecimentos de desenvolvimento front-end por meio da criação de uma interface responsiva e organizada, explorando a composição de componentes React, a estilização com CSS e o fluxo de desenvolvimento com Vite.

---

## 👨‍💻 Desenvolvimento

**MovieCity — Projeto de estudo em desenvolvimento web.**

Construído com React, JavaScript e CSS, com foco em aprendizado prático, organização e evolução contínua.

⭐ Se você gostou do projeto, considere deixar uma estrela no repositório!
