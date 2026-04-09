# 🥋 Arte Suave - Sistema de Gestão

Sistema web desenvolvido para uma organização social de Jiu-Jitsu, com o objetivo de auxiliar na gestão de alunos, pagamentos, presença e comunicação.

---

## 📌 Sobre o Projeto

Este sistema foi idealizado para apoiar um projeto social que oferece treinamento de Jiu-Jitsu para crianças, jovens e adultos, promovendo inclusão social e desenvolvimento pessoal.

A plataforma permitirá:

* 📋 Cadastro de alunos
* 💰 Controle de pagamentos (Pix/Boleto)
* 📅 Gerenciamento de presença
* 🏆 Divulgação de campeonatos
* 📧 Envio de notificações por e-mail

---

## 🧱 Arquitetura

O projeto segue uma arquitetura **em camadas**, separando responsabilidades:

* **Controller** → Recebe requisições HTTP
* **Service** → Regras de negócio
* **Repository** → Acesso ao banco de dados
* **Model** → Estrutura de dados

---

## 🖥️ Tecnologias Utilizadas

### 🔹 Backend

* Node.js
* Express
* PostgreSQL (Docker)
* Prisma ORM *(planejado)*
* JWT *(autenticação)*

### 🔹 Frontend

* React
* Vite
* TailwindCSS

---

## 📁 Estrutura do Projeto

```bash
arte-suave-estilo-de-vida/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── repositories/
│   │   ├── models/
│   │   ├── routes/
│   │   └── config/
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── routes/
│   │   └── assets/
```

---

## 🚀 Como rodar o projeto

### 🔹 Backend

```bash
cd backend
npm install
npm run dev
```

---

### 🔹 Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🌿 Padrão de Branches

Utilizamos uma estratégia baseada em Git Flow:

* `main` → Produção
* `develop` → Desenvolvimento

### 🔹 Branches de feature:

```bash
feature/nome-da-feature
```

Exemplo:

```bash
feature/login
feature/cadastro-aluno
```

---

## 👥 Equipe

* Rafael Cabral 
* Victor Emanuel
* Mel Barbosa
* Douglas Teofilo
  

---

## 📌 Status do Projeto

🚧 Em desenvolvimento

---

## 💡 Futuras melhorias

* Integração com pagamentos (Pix/Boleto)
* Sistema de notificações
* Dashboard administrativo
* Relatórios de desempenho

---

## 📄 Licença

Este projeto é acadêmico e sem fins lucrativos.
