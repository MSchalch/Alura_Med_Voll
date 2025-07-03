# 🏥 API Med Voll

Este projeto faz parte do programa **ONE - Oracle Next Education + Alura** e tem como objetivo o desenvolvimento de uma **API RESTful** para o gerenciamento de uma clínica médica. A aplicação foi construída com **Spring Boot**, aplicando boas práticas de segurança, organização de código, e arquitetura em camadas.

---

## 🔧 Funcionalidades

A API permite:

- ✅ Cadastrar, atualizar, listar, detalhar e excluir:
  - Médicos
  - Pacientes
  - Consultas
  - Usuários
- 🔐 Segurança com autenticação via JWT (token Bearer)
- 🔒 Senhas criptografadas com hash (BCrypt)
- ❌ Tratamento global de erros e exceções
- 🧪 Testes automatizados com JUnit
- 📦 Controle de versão do banco de dados via migrations (Flyway)

---

## 🛠️ Tecnologias Utilizadas

- Java 17
- Spring Boot
  - Spring Web
  - Spring Data JPA
  - Spring Security
- MySQL (banco de dados)
- Flyway (migrations)
- JUnit (testes)
- Maven

---

## 🔐 Segurança

A aplicação utiliza **autenticação JWT**:
- É necessário fazer login com e-mail e senha.
- Após autenticação, o usuário recebe um token JWT para acessar os endpoints protegidos.
- As senhas são armazenadas de forma segura usando **hash BCrypt**.

---

## 🧪 Testes

A API possui testes unitários e de integração desenvolvidos com:
- `JUnit`
- Anotações do Spring Boot para testes (`@SpringBootTest`, entre outras)

---

## 📦 Migrations

As alterações no banco de dados são feitas utilizando o **Flyway**, permitindo:
- Controle de versão do schema
- Criação automatizada de tabelas ao iniciar o projeto

---

## 🧠 Conceitos Aplicados

- Arquitetura REST
- Autenticação segura com tokens
- Criptografia de senhas
- Tratamento de exceções
- Validação com Bean Validation (`@Valid`)
- Separação entre entidades e DTOs
- Paginação de dados

---

## 👨‍💻 Autor
Matheus Schalch
- [Linkedin](https://www.linkedin.com/in/matheus-schalch-79aab6189/)
