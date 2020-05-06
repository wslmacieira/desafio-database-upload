# Desafio 06: Banco de dados e upload de arquivos no Node.js

### :rocket: Sobre o Desafio

Nesse desafio, você deve continuar desenvolvendo a aplicação de gestão de transações, treinando o que você aprendeu até agora no Node.js junto ao TypeScript, mas dessa vez incluindo o uso de banco de dados com o TypeORM e envio de arquivos com o Multer!

Essa será uma aplicação que deve armazenar transações financeiras de entrada e saída e permitir o cadastro e a listagem dessas transações, além de permitir a criação de novos registros no banco de dados a partir do envio de um arquivo csv.

###  :pencil:  Rotas da aplicação
- [x] **`POST /transactions`**
- [x] **`GET /transactions`**
- [x] **`DELETE /transactions/:id`**
- [x] **`POST /transactions/import`**


### ⚡️ Especificação dos testes
Para esse desafio temos os seguintes testes:


- [x] **`should be able to create a new transaction`**
- [x] **`should create tags when inserting new transactions`**
- [x] **`should not create tags when they already exists`**
- [x] **`should be able to list the transactions`**
- [x] **`should not be able to create outcome transaction without a valid balance`**
- [x] **`should be able to delete a transaction`**
- [x] **`should be able to import transactions`**



Feito com :purple_heart:   by [wslmacieira](https://github.com/wslmacieira) :wave:
