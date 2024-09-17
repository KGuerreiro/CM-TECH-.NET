# Challenge API

## Descrição
Esta é uma API desenvolvida utilizando ASP.NET Core Web API com uma arquitetura monolítica. A API é responsável pelo gerenciamento de usuários, cadastros e problemas relacionados a um serviço. Além disso, a API utiliza o banco de dados Oracle para persistência dos dados e o Swagger/OpenAPI para documentação dos endpoints.

# Funcionalidades

CRUD de Usuários: Permite criar, ler, atualizar e excluir informações de usuários.

CRUD de Cadastros: Permite criar, ler, atualizar e excluir cadastros de serviços.

CRUD de Problemas: Permite registrar, listar, atualizar e remover problemas associados aos cadastros.

Documentação via Swagger: Documentação automática dos endpoints para facilitar o consumo da API.

# Tecnologias Utilizadas

ASP.NET Core Web API

Oracle Database

Entity Framework Core

Swagger/OpenAPI

Arquitetura Monolítica

Padrão de Criação (Singleton)

# Requisitos

.NET 6.0 SDK

Oracle Database

Ferramenta de gerenciamento de pacotes NuGet para instalar dependências como Microsoft.EntityFrameworkCore, Microsoft.AspNetCore.Swagger, etc.

#Endpoints

# Usuários

GET /api/Usuario - Retorna todos os usuários.

GET /api/Usuario/{id} - Retorna um usuário pelo ID.

POST /api/Usuario - Cria um novo usuário.

PUT /api/Usuario/{id} - Atualiza um usuário existente.

DELETE /api/Usuario/{id} - Exclui um usuário.

# Cadastros

GET /api/Cadastro - Retorna todos os cadastros.

GET /api/Cadastro/{id} - Retorna um cadastro pelo ID.

POST /api/Cadastro - Cria um novo cadastro.

PUT /api/Cadastro/{id} - Atualiza um cadastro existente.

DELETE /api/Cadastro/{id} - Exclui um cadastro.

# Problemas

GET /api/Problemas - Retorna todos os problemas.

GET /api/Problemas/{id} - Retorna um problema pelo ID.

POST /api/Problemas - Registra um novo problema.

PUT /api/Problemas/{id} - Atualiza um problema existente.

DELETE /api/Problemas/{id} - Exclui um problema.
