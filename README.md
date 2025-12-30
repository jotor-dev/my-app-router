# React Router Starter 🚀

Uma estrutura inicial robusta para aplicações React modernas, utilizando navegação dinâmica com Vite.

## 🌟 Funcionalidades

* **Navegação Declarativa**: Gerenciamento de rotas com `react-router-dom` v6.
* **Desenvolvimento Ultra-rápido**: Configurado com **Vite** para HMR (Hot Module Replacement) instantâneo.
* **TypeScript**: Tipagem estática em toda a aplicação, incluindo componentes e rotas.
* **Componentização**: Estrutura organizada com componentes globais (Header) e páginas independentes.

## 🛠️ Tecnologias Utilizadas

* **Core**: [React 18](https://reactjs.org/)
* **Build Tool**: [Vite](https://vitejs.dev/)
* **Linguagem**: [TypeScript](https://www.typescriptlang.org/)
* **Roteamento**: [React Router DOM v6](https://reactrouter.com/)
* **Qualidade de Código**: [ESLint](https://eslint.org/)

## 📂 Estrutura de Rotas

A aplicação está configurada com as seguintes rotas principais:

| Caminho | Componente | Descrição |
| --- | --- | --- |
| `/` | `Home` | Página principal da aplicação. |
| `/about` | `About` | Página de informações sobre o projeto. |

## 🔧 Instalação e Execução

1. **Clone o repositório:**
```bash
git clone https://github.com/jotor-dev/my-app-router.git
cd my-app-router
```
2. **Instale as dependências:**
```bash
npm install
```
3. **Inicie o servidor de desenvolvimento:**
```bash
npm run dev
```
4. **Acesse no navegador:**
O projeto estará disponível em `http://localhost:5173`.


## 📐 Organização do Código

O arquivo principal `App.tsx` atua como o **Router Provider**, centralizando a lógica de navegação:

* **`<Header />`**: Componente persistente que aparece em todas as rotas.
* **`<Routes>`**: Gerenciador que renderiza o componente específico baseado na URL atual.
