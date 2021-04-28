# Mytodo Backend

Esse é o backend do app Mytodo feito com [STRAPI](https://strapi.io/)


# Instalação


Após clonar o repositório, crie um arquivo `.env` na raiz do projeto e configure ele com base no arquivo `.env.example`. Seu arquivo `.env` deve ficar assim:

```bash
DATABASE_HOST=cluster0.blah.mongodb.net
DATABASE_NAME=myFirstDatabase
DATABASE_USERNAME=admin
DATABASE_PASSWORD=yourpassword
```
 :warning: **_NOTE:_** Caso queira utilizar um banco de dados que nçao seja o MongoDb por favor olhe a documentação do [Strapi aqui](https://strapi.io/documentation/developer-docs/latest/setup-deployment-guides/configurations.html#database)

 Após configurar o arquivo `.env` execute o comando no terminal para iniciar o strapi:

 ```bash
  npm run develop
 ```
Ou
 ```bash
  yarn develop
 ```

 Depois de iniciar o strapi vá até http://localhost:1337/admin para configuar o usuário admin, e poder realizar suas alterações desejadas
