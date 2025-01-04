# Todo-Task - Task Management Application

## Descrição

**Todo-Task** é uma aplicação de gerenciamento de tarefas desenvolvida utilizando **Java Spring**. O objetivo deste projeto é permitir que os usuários possam adicionar, editar, excluir e listar suas tarefas diárias de maneira simples e eficiente. A aplicação também inclui funcionalidades como autenticação de usuários, controle de acesso e persistência de dados.

## Funcionalidades

- **Autenticação de Usuário**: Login e registro de usuários com autenticação baseada em **JWT** (JSON Web Token).
- **Gerenciamento de Tarefas**: CRUD (Create, Read, Update, Delete) para tarefas.
- **Filtros de Tarefas**: Filtro por status de conclusão (pendente, concluída).
- **Notificações**: Notificações por e-mail quando uma tarefa for concluída.
- **Paginação**: Paginação da lista de tarefas.
- **Testes Automatizados**: Testes unitários e de integração para garantir a qualidade do código.

---

## Requisitos

### Requisitos Funcionais

1. **Autenticação de Usuário**:
   - O sistema deve permitir que os usuários se registrem no sistema, fornecendo um nome de usuário, email e senha.
   - O sistema deve permitir que os usuários façam login com seu nome de usuário/email e senha.
   - O sistema deve gerar um **JSON Web Token (JWT)** após a autenticação bem-sucedida, permitindo ao usuário acessar as APIs protegidas.

2. **Gerenciamento de Tarefas**:
   - O sistema deve permitir que o usuário crie novas tarefas, com título, descrição, data de criação e status.
   - O sistema deve permitir que o usuário edite suas tarefas.
   - O sistema deve permitir que o usuário exclua tarefas.
   - O sistema deve permitir que o usuário visualize uma lista de suas tarefas.
   - O sistema deve permitir que o usuário filtre tarefas por status (pendente, concluída).

3. **Segurança**:
   - O sistema deve garantir que apenas usuários autenticados possam acessar suas tarefas, utilizando **JWT** para autorização.

4. **Notificações**:
   - O sistema deve enviar uma notificação por **email** quando uma tarefa for concluída.

5. **Paginação**:
   - O sistema deve permitir a visualização de tarefas de forma paginada.

6. **Filtros**:
   - O sistema deve permitir que o usuário filtre suas tarefas por status ou data de vencimento.

---

### Requisitos Não Funcionais

1. **Desempenho**:
   - O sistema deve ser capaz de processar até **1000 tarefas** de um único usuário de forma eficiente.

2. **Escalabilidade**:
   - O sistema deve ser escalável para suportar um número crescente de usuários.

3. **Segurança**:
   - A aplicação deve seguir as melhores práticas de segurança, incluindo criptografia de senhas e proteção contra ataques comuns.

4. **Manutenibilidade**:
   - O código deve ser bem estruturado, modular e documentado para facilitar futuras manutenções.

5. **Disponibilidade**:
   - O sistema deve estar disponível 99% do tempo, com backups regulares dos dados.

---

## Tecnologias Usadas

- **Java 17**
- **Spring Boot** (para construir a API)
- **Spring Security** (para autenticação e autorização)
- **JWT** (para autenticação de usuários)
- **Spring Data JPA** (para interação com o banco de dados)
- **MySQL** (banco de dados relacional)
- **Swagger** (para documentação da API)
- **JUnit** e **Mockito** (para testes automatizados)

---

## Como Contribuir

1. Fork este repositório.
2. Crie uma branch para a sua feature (`git checkout -b minha-feature`).
3. Faça commit das suas alterações (`git commit -am 'Adicionando nova funcionalidade'`).
4. Envie para o repositório remoto (`git push origin minha-feature`).
5. Abra um Pull Request.

