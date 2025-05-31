# 🧠 User API (NestJS + In-Memory Storage)

Esta é uma API REST simples construída com [NestJS](https://nestjs.com/) que permite armazenar, consultar e excluir usuários diretamente na memória (sem banco de dados).

---

## 🚀 Funcionalidades

- ✅ Criar usuário (`POST /users`)
- ✅ Listar todos os usuários (`GET /users`)
- ✅ Buscar um usuário por ID (`GET /users/:id`)
- ✅ Deletar usuário (`DELETE /users/:id`)

---

## 📦 Tecnologias

- [Node.js](https://nodejs.org/)
- [NestJS](https://nestjs.com/)
- [TypeScript](https://www.typescriptlang.org/)

---

## 📁 Estrutura do Projeto

\`\`\`
user-api/
├── src/
│   ├── main.ts
│   ├── app.module.ts
│   └── users/
│       ├── users.controller.ts
│       ├── users.service.ts
│       ├── users.module.ts
│       ├── dto/
│       │   └── create-user.dto.ts
│       └── user.entity.ts
├── package.json
└── tsconfig.json
\`\`\`

---

## ▶️ Como rodar o projeto

### 1. Instale as dependências

\`\`\`bash
npm install
\`\`\`

### 2. Rode o servidor

\`\`\`bash
npm run start
\`\`\`

A API estará disponível em:  
\`http://localhost:3000\`

---

## 🧪 Exemplos de uso

### ➕ Criar usuário

**POST** \`/users\`

\`\`\`json
{
  "name": "João da Silva",
  "email": "joao@email.com"
}
\`\`\`

### 📋 Listar todos os usuários

**GET** \`/users\`

### 🔍 Obter um usuário por ID

**GET** \`/users/1\`

### ❌ Deletar um usuário

**DELETE** \`/users/1\`

---

## ⚠️ Observação

> Esta API usa **armazenamento em memória**, ou seja, os dados serão perdidos ao reiniciar o servidor. Ideal para testes ou aprendizado com NestJS.

---

## 📃 Licença

MIT © 2025
