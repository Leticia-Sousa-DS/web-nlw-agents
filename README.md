# Web (NLW Agents)

Este projeto foi desenvolvido durante o evento **NLW Agents** promovido pela Rocketseat. Trata-se de uma aplicação web moderna utilizando React, com foco em boas práticas, componentização e experiência do usuário.

## Tecnologias e Bibliotecas Utilizadas

- **React 19** – Biblioteca principal para construção da interface.
- **React Router DOM 7** – Gerenciamento de rotas SPA.
- **@tanstack/react-query** – Gerenciamento e cache de dados assíncronos.
- **Tailwind CSS 4** – Utilitário para estilização rápida e responsiva.
- **shadcn/ui** – Componentes de UI reutilizáveis e acessíveis, estilizados com Tailwind CSS.
- **Radix UI** – Base de acessibilidade e comportamento dos componentes shadcn/ui.
- **Lucide React** – Ícones SVG.
- **class-variance-authority, clsx, tailwind-merge** – Utilitários para manipulação de classes CSS.
- **TypeScript** – Tipagem estática.
- **Vite** – Bundler e ambiente de desenvolvimento rápido.
- **Biome** – Linter e formatter.

## Estrutura e Padrões de Projeto

- **Componentização**: Os componentes de UI são baseados em [shadcn/ui](https://ui.shadcn.com/), localizados em `src/components/ui/`, seguindo uma abordagem modular e acessível.
- **Páginas**: As views principais estão em `src/pages/` e são conectadas via React Router.
- **Gerenciamento de estado e dados**: Utiliza React Query para requisições e cache.
- **Estilização**: Tailwind CSS configurado via `src/index.css`, com custom properties.
- **Organização**: Separação clara entre componentes de UI, páginas e utilitários (`src/lib/utils.ts`).

## Estrutura do Projeto

```text
src/
├── components/   # Componentes de interface (UI)
│   └── ui/       # Componentes reutilizáveis (shadcn/ui)
├── pages/        # Páginas da aplicação (views)
├── lib/          # Funções utilitárias
├── index.css     # Estilos globais e Tailwind CSS
├── app.tsx       # Componente principal da aplicação
├── main.tsx      # Ponto de entrada do React
```

## Como rodar o projeto

1. **Clone o repositório**
   ```bash
   git clone <url-do-repo>
   cd web
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Rode o projeto em modo desenvolvimento**
   ```bash
   npm run dev
   ```

4. **Acesse no navegador**
   ```
   http://localhost:5173
   ```

## Scripts disponíveis

- `npm run dev` – Inicia o servidor de desenvolvimento.
- `npm run build` – Gera a build de produção.
- `npm run preview` – Visualiza a build de produção localmente.

## Observações

- O projeto utiliza **TypeScript** e segue boas práticas de tipagem.
- O padrão de organização facilita a escalabilidade e manutenção.
- Componentes de UI baseados em **shadcn/ui**.
- Desenvolvido durante o evento **NLW Agents** da Rocketseat.
- **Importante:** Certifique-se de que o backend (API) esteja rodando em `http://localhost:3333` para o funcionamento correto das requisições. 