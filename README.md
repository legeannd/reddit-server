# Reddit Server
![stacks](https://img.shields.io/badge/NodeJS-v12.18.4-brightgreen) ![stacks](https://img.shields.io/badge/Express-v4.17.1-brightgreen) ![stacks](https://img.shields.io/badge/GraphQL-v15.3.0-brightgreen) ![stacks](https://img.shields.io/badge/ioredis-v4.17.3-brightgreen) ![stacks](https://img.shields.io/badge/TypeORM-v0.2.26-brightgreen) ![stacks](https://img.shields.io/badge/Stack-Typescript-blue) ![GitHub](https://img.shields.io/github/license/legeannd/reddit-server)

* [Content (en-US)](#secao-en_us)
* [Conteúdo (pt-BR)](#secao-pt_br)

---

## About the project <a id="secao-en_us"></a>

This is a NodeJS server based on the main functionalities of Reddit's site.
In the server, users can create an account, login, change account password through recovery email, create a post, see all the posts, edit a post, delete a post, and upvote and downvote posts. Each users are able to see its own upvotes and downvotes in a post, and delete and update only its own posts.

The database was created using Postgres and the routes were created using GraphQL, and Redis was used to cache posts. The emails were sent using Nodemailer.

The frontend of the app can be found [here](https://github.com/legeannd/reddit-web).

## Content
  * [Techs](#techs)
  * [How to run the project](#installation)

## Techs <a id="techs"></a>

- [x] NodeJS
- [x] Express
- [x] GraphQL
- [x] ioredis
- [x] Postgres
- [x] TypeORM
- [x] Nodemailer

## How to run the project <a id="installation"></a>
To run the project, you'll need to have Node and NPM or Yarn installed to setup all the dependencies.

Install all dependencies using the `yarn` command, run `yarn dev` in one terminal, and `yarn watch` in another terminal to build project and watch changes, and open the GraphQL playground to do some API requests on `localhost:4000/playground`.

---

## Sobre o projeto <a id="secao-pt_br"></a>

Este é um servidor em NodeJS baseado nas funcionalidades principais do site do Reddit. No servidor, os usuários podem criar uma conta, fazer login, mudar a senha da conta através do email, criar um post, ver todos os posts, editar um post, deletar um post, e dar upvote e downvote nos posts. Todos os usuários podem ver seus próprios upvotes e downvotes em um post, e deletar e atualizar apenas seus próprios posts.

O banco de dados foi criado usando Postgres e as rotas foram criadas usando GraphQL, e o Redis foi usado para fazer cache dos posts. Os emails foram enviados utilizando o Nodemailer.

O front-end do app pode ser encontrado [aqui](https://github.com/legeannd/reddit-web).

## Conteúdos
  * [Tecnologias](#tecnlogias)
  * [Como executar o projeto](#instalacao)

## Techs <a id="tecnlogias"></a>

- [x] NodeJS
- [x] Express
- [x] GraphQL
- [x] ioredis
- [x] Postgres
- [x] TypeORM
- [x] Nodemailer

## Como executar o projeto <a id="instalacao"></a>
Para executar o projeto, você irá precisar ter o Node e o NPM ou Yarn instalados para baixar as dependências.

Instale todas as dependencias utilizando o comando `yarn`, e rode o comando `yarn dev` em um terminal, e `yarn watch` em outro terminal para fazer o build do projeto e observar mudanças, e abra o GraphQL playground para fazer requisições à API em `localhost:4000/playground`.

---
###### Developed by [Gean Lucas](https://www.linkedin.com/in/geanlucaas/) :rocket:.
