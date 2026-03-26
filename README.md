Sistema de Controle de Estoque

Este projeto é uma API desenvolvida para gerenciar o fluxo de entrada e saída de produtos em um estoque, garantindo controle, integridade dos dados e evitando inconsistências.

O sistema permite cadastrar, listar, buscar e remover itens do estoque utilizando um banco de dados SQLite integrado com Entity Framework Core.

Participante:

Pedro Henrique Basilio

Funcionalidades

A API oferece operações essenciais para o gerenciamento de produtos:

Endpoints
Método	Rota	Descrição
GET	/products	Lista todos os produtos cadastrados
GET	/products/{id}	Busca um produto específico por ID
POST	/products	Cadastra um novo produto no estoque
DELETE	/products/{id}	Remove um produto do estoque

Tecnologias Utilizadas
C# / .NET
Entity Framework Core
Microsoft.EntityFrameworkCore
Microsoft.EntityFrameworkCore.Design
Microsoft.EntityFrameworkCore.Tools
Microsoft.EntityFrameworkCore.Sqlite
Swagger (Swashbuckle.AspNetCore)
SQLite (estoque.db)

Estrutura do Projeto
/
├── Models/               # Modelo de dados (Produto)
├── Data/                 # Contexto do banco (SQLite)
├── Routes/               # Rotas e endpoints da API
├── Migrations/           # Migrações do Entity Framework
├── wwwroot/              # Arquivos estáticos
├── Program.cs            # Configuração da aplicação
├── appsettings.json      # Configurações gerais
└── estoque.db            # Banco de dados SQLite

Como Executar
Certifique-se de ter o .NET SDK instalado.

No terminal, acesse o projeto:

cd Estoque-e-compras

Execute o projeto:

dotnet run

Acesse o Swagger para testar a API:

http://localhost:5000/swagger
