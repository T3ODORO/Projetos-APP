# API para Gestão de Médicos e Pacientes 🏥

Este repositório contém uma aplicação desenvolvida em Java com Spring Boot para gerenciar informações de médicos e pacientes. O projeto segue o padrão REST e inclui operações CRUD (Create, Read, Update, Delete) para facilitar a administração dos dados. Além disso, utiliza validação de dados, mapeamento relacional e implementação de boas práticas de design de software.

<p align="center">
    <b>Projeto desenvolvido para estudo de APIs RESTful e boas práticas em Java Spring.</b>
</p>

---

## ✨ Funcionalidades

- **Gerenciamento de Médicos**:
  - Cadastro de médicos com informações detalhadas (nome, e-mail, CRM, especialidade, endereço).
  - Atualização de dados, incluindo informações pessoais e endereço.
  - Exclusão lógica, desativando o médico sem removê-lo do banco de dados.
  - Listagem paginada com detalhes relevantes.

- **Gerenciamento de Pacientes**:
  - Cadastro de pacientes com validação de dados.

- **Validação e Segurança**:
  - Validação automática de entradas usando anotações do Bean Validation.
  - Operações transacionais para consistência de dados.

---

## 🛠️ Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 3** (Spring Data JPA, Spring Web, Validation)
- **Hibernate** para persistência de dados
- **MySQL** como banco de dados relacional
- **Lombok** para redução de boilerplate no código
- **Flyway** para versionamento do banco de dados

---

## 📋 Pré-requisitos

Certifique-se de ter as ferramentas necessárias instaladas antes de executar a aplicação:

- **Java 17**: [Instalar Java](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)
- **Maven**: [Instalar Maven](https://maven.apache.org/install.html)
- **MySQL**: Configure um banco de dados local com as credenciais:
  - URL: `jdbc:mysql://localhost/api`
  - Usuário: `[user]`
  - Senha: `[password]`

---

## 🚀 Como Executar

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/nome-repositorio.git
   cd nome-repositorio
