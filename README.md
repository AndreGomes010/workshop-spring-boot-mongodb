# 📦 Workshop Spring Boot + MongoDB

Projeto desenvolvido como exercício prático de CRUD com Java, Spring Boot e banco de dados MongoDB.

## 🔧 Funcionalidades

- Cadastro de usuários
- Cadastro de posts vinculados a usuários
- Operações de leitura, atualização e exclusão (CRUD)
- Associação entre entidades (User e Post)
- Uso de padrão DTO para transferência de dados
- Integração com banco de dados NoSQL (MongoDB)

## 🛠️ Tecnologias utilizadas

- Java 17
- Spring Boot
- MongoDB
- Maven
- Postman (para testes de API)
- Git

## ▶️ Como executar o projeto

1. Clone este repositório:

```bash
git clone https://github.com/AndreGomes010/workshop-spring-boot-mongodb.git
Certifique-se de que o MongoDB está rodando localmente (porta padrão 27017)

Importe o projeto em sua IDE (IntelliJ, VS Code ou Eclipse)

Execute a classe principal:

java

com.andregomes.workshopmongo.WorkshopSpringbootMongodbApplication
Teste os endpoints da API com Postman ou outra ferramenta REST

📂 Estrutura básica
domain: entidades do sistema (User, Post, etc.)

repository: interfaces para acesso ao MongoDB

services: regras de negócio

resources: controladores REST

👨‍💻 Autor
André Gomes
