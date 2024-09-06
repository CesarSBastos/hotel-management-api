# Api com Autenticação e autorização

## Getting Started

### Dependências

* As dependências já estão listadas no package.json
* Dentro da pasta db-script está o código SQL a ser utilizado para criar as tabelas e instâncias em um Banco POSTGRES
* Um arquivo thunder-collection foi uncluído ao projeto para facilitar a testagem dos endpoints. Você pode importá-lo dentro do thunder-client (extensão vscode para testar apis rest ou mesmo no postman ou insomnia).
* Configure o arquivo .env com as suas credenciais

### Instalação

Faça um clone desse repositório e depois execute: npm install

### Executando a API

Para rodar a API execute, de dentro da raiz do proejeto: node index.js 
Recomendado:
Utilize o nodemon.
npm install -g nodemon
nodemon index.js
