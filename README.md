# Servidor e Cliente em Java com Spring Boot

Este projeto demonstra como criar um **Servidor** utilizando o framework **Spring Boot** e um **Cliente** em Java que se comunica com o servidor através de requisições HTTP. O servidor implementa uma API RESTful simples, enquanto o cliente consome os dados expostos por essa API.

## Funcionalidades

- Servidor Spring Boot expõe endpoints REST para manipulação de dados.
- Cliente Java se comunica com o servidor utilizando requisições HTTP (GET, POST).
- O cliente pode:
  - Buscar uma lista de usuários.
  - Adicionar novos usuários.
  
---

## Tecnologias Utilizadas

### Servidor (Spring Boot)

- **Spring Boot**: Framework para criação de aplicações Java simplificadas.
- **Spring Web**: Para implementar a API REST.
- **Spring Data JPA** (opcional): Para persistência de dados em um banco de dados.
- **H2 Database** (opcional): Banco de dados em memória para testes.

### Cliente (Java)

- **Java HTTP Client**: Para realizar requisições HTTP.
- **Gson** (ou Jackson): Para serialização e desserialização de objetos JSON.

---

## Estrutura do Projeto

### 1. Servidor (API REST)

O servidor é uma aplicação Spring Boot que expõe endpoints REST para permitir que o cliente se conecte e envie ou obtenha dados. 

### Exemplo de Endpoints

- `GET /api/users`: Retorna uma lista de usuários.
- `POST /api/users`: Cria um novo usuário.
- `GET /api/users/{id}`: Retorna os detalhes de um usuário específico.

### 2. Cliente (Java)

O cliente faz requisições HTTP para os endpoints do servidor para consumir e enviar dados.

---

## Configuração do Servidor (Spring Boot)

### Pré-requisitos

- **JDK 11+**
- **Maven ou Gradle** (para gerenciar dependências)
- **IDE Java** (como IntelliJ IDEA, Eclipse)

