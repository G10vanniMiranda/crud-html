### API

GET:: LISTAGEM :: http://localhost:3000/login

DELETE:: DELETE http://localhost:3000/login/1


POST:: INSERIR :: http://localhost:3000/login
    {
        "email": "xico@gmail.com",
        "senha": "123"
    }

PUT/PATCH:: ATUALIZAR :: http://localhost:3000/login/1
    {
        "email": "xico@gmail.com",
        "senha": "123"
    }


http://localhost:3000/login


http://localhost:3000/categoria

### para rodar o projeto
```
npx json-server banco2024.json
```