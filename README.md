## ✅ FRONTEND – ControleSimples (React + Angular + Testes)

### 🧱 Estrutura Proposta

```
ControleSimples.Frontend/
├── cliente-app/                 # React (cliente final, mobile friendly)
│   ├── pages/
│   ├── components/
│   ├── hooks/
│   ├── services/
│   └── tests/
├── admin-app/                   # Angular (painel administrativo)
│   ├── modules/
│   ├── components/
│   ├── guards/
│   ├── services/
│   └── tests/
├── shared-ui/                   # Biblioteca compartilhada de componentes
├── README.md
└── .editorconfig
```

### 🚀 Tecnologias

| Stack             | Ferramenta                                   |
|-------------------|-----------------------------------------------|
| React App         | Vite + TailwindCSS + Zustand (estado leve)    |
| Angular App       | Angular 17 + RxJS + NGXS                      |
| API Client        | React Query (React) / HttpClient (Angular)    |
| Autenticação      | Supabase Auth (com JWT compartilhado)         |
| Testes Unitários  | Jest + Testing Library                        |
| Testes E2E        | Cypress ou Playwright                         |
| Deploy            | Vercel (React) / Firebase ou App Service (Angular) |

### 📋 Funcionalidades Iniciais

| App              | Módulos                                        |
|------------------|------------------------------------------------|
| **cliente-app**  | Dashboard, Estoque, Agenda, Pedidos            |
| **admin-app**    | Cadastro de empresas, permissões, relatórios   |
| **Ambos**        | Login, Perfil, Alterar senha, Logout           |

### 🎯 Padrões de UX

- Interface intuitiva, com foco em **usuário leigo**
- **Acessibilidade** garantida (ARIA + contraste)
- Design Mobile First
- Componentes reutilizáveis entre apps (ex: botões, inputs, modais)
