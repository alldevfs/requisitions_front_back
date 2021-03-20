

# Infobase: Sobre os módulo, foram usados o express, nodemon, cors, axios.  
> Inicie o projeto.
- 'npm init -y' 

> instale as dependencias do projeto npm install express nodemon cors axios. 
> Crie a rota de acesso a API.
> Serv a API.
> Ativar o Cors.
> Ativar o Nodemon. Ele ajuda a reiniciar o serv caso haja mudanças no script.
  Acesse o package.json e altere a parte de scripts para
- "scripts": {
-    "start": "nodemon server.js"
-   },

* caso deseje utilizar o autoload da pagina html use o npx lite-server, idem ao nodemon.

> Use fetch para consumir API pelo front-end
> Use async e await quando pegar informações
> inclua Try Catch para controle de inconsistências
> Exiba as informações na tela

> Consuma uma API pelo back-end.
- pode utilizar o jsonplaceholder 'https://jsonplaceholder.typicode.com/users/1/todos'.
> Use o axios para consumir a API pelo back-end, ele ja vem em json e pode usar da extração de dados para resumir o resultado { data }.
> Inclua o try Catch ao consumir api pelo back-end
