# 🏋️ Aplicação de Check-ins em Academias (GymPass Style App)

Este projeto é uma aplicação para gerenciamento de check-ins em academias, seguindo as melhores práticas de desenvolvimento, incluindo SOLID, Design Patterns e autenticação segura.

## 🚀 Tecnologias e Conceitos Utilizados

- **SOLID & Design Patterns** – Código modular e reutilizável utilizando padrões como Repository Pattern e Factory Pattern.
- **Banco de Dados com Docker** – Facilita a configuração e garante um ambiente consistente.
- **Autenticação Segura** – Implementação de JWT e Refresh Token para gerenciar sessões de usuários.
- **RBAC (Role-Based Access Control)** – Controle de permissões baseado em papéis.
- **Experiência do Usuário Aprimorada** – Check-ins rápidos e eficientes.

---

## ✅ RFs (Requisitos Funcionais)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter o seu histórico de check-ins;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia;

---

## ⚖️ RNs (Regras de Negócio)

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [ ] O check-in só pode ser validado até 20 minutos após ser criado;
- [ ] O check-in só pode ser validado por administradores;
- [ ] A academia só pode ser cadastrada por administradores;

---

## 🔒 RNFs (Requisitos Não-Funcionais)

- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [ ] Todas listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);
