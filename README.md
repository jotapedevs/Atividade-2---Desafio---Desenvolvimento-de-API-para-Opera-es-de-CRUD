# Atividade-2---Desafio---Desenvolvimento-de-API-para-Opera-es-de-CRUD

### Rotas

- **GET `/users`**: Retorna todos os usuários salvos no banco.
- **POST `/users`**: Cria um novo usuário.
- **PATCH `/users/:id`**: Atualiza um usuário existente pelo `id`.
- **DELETE `/users/:id`**: Deleta um usuário existente pelo `id`.

### Crie um .env
   ```env
   PORT=8000
   MONGODB_URL=URL do MongoDB, ex: mongodb+srv://#####.#####.mongodb.net
   MONGODB_USERNAME=SeuLoginNoMongoDB
   MONGODB_PASSWORD=SuaSenhaNoMongoDB
   ```
