To-Do List App (React + Vite + Tailwind)

Aplicativo simples e rápido para criar, concluir e excluir tarefas. Feito com React, Vite e Tailwind CSS, focado em produtividade, acessibilidade e UI limpa.

✨ Recursos

Adicionar, concluir e remover tarefas

Persistência local com localStorage

Interface responsiva com Tailwind

Componentização com React Hooks

🧱 Tecnologias

React 18 + Vite

TypeScript (se aplicável ao seu template)

Tailwind CSS 3

ESLint + Prettier (opcional)
```bash
# 1) Instalar dependências
npm install
```
```bash
# 2) Rodar em desenvolvimento
npm run dev
```
```bash
# 3) Build de produção
npm run build
```
```bash
# 4) Pré-visualizar o build
npm run preview
```

```bash
todo-app/
├─ public/
├─ src/
│  ├─ components/
│  ├─ assets/
│  ├─ App.tsx
│  ├─ main.tsx
│  └─ index.css
├─ index.html
├─ package.json
└─ tailwind.config.js
```

Tailwind (configuração básica)
```bash
tailwind.config.js
export default {
  content: ["./index.html", "./src/**/*.{ts,tsx,js,jsx}"],
  theme: { extend: {} },
  plugins: [],
};

src/index.css
@tailwind base;
@tailwind components;
@tailwind utilities;

```
💡 Como usar

Digite o nome da tarefa e pressione Enter (ou clique em “Adicionar”).

Clique na tarefa para marcar como concluída (estilo riscado).

Use o ícone de lixeira para excluir.

As tarefas ficam salvas no localStorage.

♿ Acessibilidade

Elementos clicáveis com role/labels quando necessário

Estados visuais de foco (focus ring do Tailwind)

Navegação por teclado

🧭 Roteiro (Roadmap)

 Filtro por status (Todas | Ativas | Concluídas)

 Edição inline de tarefa

 Drag & drop para reordenar

 Contador de tarefas

 Testes com Vitest/React Testing Library

 Este projeto foi feito com intenções de estudo e prática, servindo como laboratório para experimentar React e Tailwind. Parte das soluções e do design tiveram inspirações em vídeos do YouTube e materiais da comunidade.
