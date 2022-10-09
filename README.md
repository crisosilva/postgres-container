# postgres-container

Projeto de container contendo banco de dados Postgres e Pgadmin para integração com banco de dados.

## Acesso do PgAdmin
Para acessar o PgAdmin basta subir o compose e acessar o PgAdmin via navegador pela porta localhost:16543 (o PgAdmin pode demorar alguns segundos até ficar disponível). O usuário é **seu_email@gmail.com** e senha é **Senha123**.


Na tela de login podemos alterar o idioma para português, por padrão a língua inglesa vem selecionada.

## Criando o primeiro database
Devemos relizar a conexão com o servidor e após já podemos criar o nosso primeiro database.

O nome do host é o mesmo nome do container e pode ser encontrado quando subir o container com o ´´´docker compose up´´´ ou digitando ´´´docker compose ps´´´, o username usado foi o **postgres** e a senha **Senha123**. Lembarndo que os parametros podem ser alterados no arquivo compose.
