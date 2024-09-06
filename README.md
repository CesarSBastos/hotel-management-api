# Hotel Management API
Este projeto é uma API RESTful para gerenciar operações de um hotel, como reservas de quartos, gerenciamento de clientes, disponibilidade de quartos, entre outros, com uso de tecnologias modernas como Sequelize, JWT e Node Cache.

## Funcionalidades
 Sequelize ORM: Gerencia interações com o banco de dados usando modelos de quartos, reservas e clientes.
 Autenticação JWT: Protege endpoints críticos da API, garantindo que apenas usuários autenticados possam acessar ou modificar dados sensíveis.
 Node Cache: Utilizado para cachear dados frequentemente acessados, como a disponibilidade de quartos, melhorando o desempenho.
 Paginação: Permite a recuperação de dados em páginas para facilitar a navegação em grandes volumes de informações.
## Tecnologias
 Node.js com Express
 Sequelize (PostgreSQL ou MySQL)
 JWT para autenticação
 Node Cache para caching de dados
 Swagger para documentação da API
## Configuração
 Clone o repositório:
```
git clone https://github.com/CesarSBastos/hotel-management-api.git
```
## Instale as dependências:
```
npm install
```
## Configure as variáveis de ambiente (baseado no .env.example):
```
cp .env.example .env
```
## Execute as migrações do banco de dados:
```
npx sequelize-cli db:migrate
```
## Inicie o servidor:
```
npm start
```

### Caching
O Node Cache é utilizado para armazenar em cache dados frequentemente acessados, como a disponibilidade de quartos, reduzindo a carga no banco de dados e aumentando a performance.

### Autenticação
O JWT é usado para proteger endpoints sensíveis. Apenas usuários autenticados com um token válido podem realizar operações como criar, atualizar ou excluir reservas e quartos.

### Paginação
A API suporta paginação em todos os endpoints de listagem, utilizando os parâmetros de query:

page: Número da página (padrão é 1).
size: Número de itens por página (padrão é 10).

## Contribuição
Sinta-se à vontade para enviar issues ou pull requests para melhorar o projeto.

