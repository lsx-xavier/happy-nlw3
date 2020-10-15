# Anotações (estudos 📑)

- Rota = Conjunto (https://localhost.com | https://localhost.com/users)
- Recursos = usuário (.../user | .../perfil | .../contato)

- Métodos HTTP = GET, POST, PUT, DELE
  - GET = Buscar uma informação (Lista | 1 item) **Conseguimos acessar a rota normalmente no navegador!**
  - POST = Criar uma informação
  - PUT = Editar uma informação
  - DELETE = Deletar uma informação

- Parâmetros
  - Query Params = Enviados diretamente na rota (http://localhost.com:3333/users?*search=diego*) _Buscando o Query = request.query_
  - Route Params = Enviados na rota mas sem nomes, identificar um recurso ( http://localhost.com:3333/users/*1*) _Buscando o Route = request.params_
  - Body = Corpo da requisição, enviar dados especificos de um formulário, geralmente. _Buscando o Body = request.body_

- Driver nativo = permite executar direto no node mas sem abstração, precisa escrever a query no mesmo formato que no banco de dados;
- Query builder (knex.js famoso) = escrevemos as query com javascript.js, praticamente como um construtor de query;
- ORM (object relational mapping) = uma class do javascript que simboliza a tabela do banco de dados;

- Banco de dados (Sqlite)
  - migrations = Esse arquivo contem todas as linhas de comando para criar as tabelas;


- Bibliotecas:
 - Multer = lidar com upload de arquivos dentro do node;


# Entrar em contato!

<a href="https://www.linkedin.com/in/lucas-xavier-588b67a6/" target="_blank" >
  <img alt="Linkedin - Lucas Xavier" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
</a>&nbsp;&nbsp;&nbsp;
<a href="mailto:ls.xxavier@gmail.com" target="_blank" >
  <img alt="Email - Lucas Xavier" src="https://img.shields.io/badge/Email--%23F8952D?style=social&logo=gmail">
</a> 

Lucas Xavier