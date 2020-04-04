![heroes](https://user-images.githubusercontent.com/35976070/78409429-07128600-75e0-11ea-8e0c-a2fdad57b56a.png)

# Be The Hero
Projeto desenvolvido na Semana Oministack 11

## Tecnologias envolvidas

Este projeto foi desenvolvido usando no

### Front-end

* [React](https://pt-br.reactjs.org/) Uma biblioteca interativa para criar interfaces com o usuário.



### Back-end

* [Node.js](https://nodejs.org/en/) é um runtime JavaScript desenvolvido com o Chrome's V8 JavaScript engine. Basicamente.

* [SQLite](https://www.sqlite.org/index.html) banco de dados do tipo SQL usado na aplicacao, juntamente com [KNEX](http://knexjs.org/).



### Mobile
* [React Native](https://reactnative.dev/) Com o lema: "Learn once, write anywhere", utiliza os mesmos conceitos do React para criar interfaces nativas para dispositivos móveis. Com um código e uma linguagem é possível criar apps para Android e iOS.

* [Expo](https://expo.io/) É um framework e uma plataforma universal para aplicação React, definindo ferramentas construídas em React Native e plataformas nativas que ajudam o desenvolvedor a construír, lançar e interagir rapidamente no iOS e Android a partir do mesmo código JavaScript/TypeScript.



## O que desenvolvemos?

Uma aplicação para que ONG's possam divulgar seus casos e conseguir financiamento voluntário para cada um deles.

### 1º Dia

Foi apresentado o projeto, Desenvolvido o UI e o UX no figma. Também fizemos o ritual do "Hello World" em cada tecnologia utilizada. É possível acessar esses tutoriais aqui:

* [NodeJS](https://nodejs.org/en/docs/guides/getting-started-guide/)
* [React](https://reactjs.org/docs/hello-world.html)

### 2º Dia - Back
No segundo foi desenvolvido a base da aplicação, ou seja o back-end da aplicação com as seguintes tecnologias:

[NodeJS](https://nodejs.org/en/docs/guides/getting-started-guide/) Utilizamos o nodejs como base da aplicação para gerenciar a conexão entre o front-end e o banco de dados. Foram utilizadas as seguintes bibliotecas:

[Express](https://expressjs.com/) => Utilizado para gerenciar as requisições, rotas e URLS.

[Nodemon](https://nodemon.io/) => Utilzado para monitorar as alterações em todos os arquivo e dar "restart" no servidor.

[SQLite](https://www.sqlite.org/index.html) => Para o banco de dados.

[Knex](http://knexjs.org/) => Para gerenciar o banco de dados, com o CRUD completo. O banco de dados foi instalado através do Knex conforme mostrado [aqui](http://knexjs.org/#Installation).

[CORS](https://expressjs.com/en/resources/middleware/cors.html) => Para permitir o acesso do front-end e mobile à aplicação.

### Definição de Entidades e Funcionalidades:
#### Entidades:
 * ONG
 * Caso (Incident)
### Funcionalidades
 * Login/Logout da ONG
 * Cadastro da ONG
 * Deletar Casos
 * Listar casos específicos de uma ONG
 * Listar todos os casos
 * Entrar em contato com a ONG

### 3º Dia - Front
Nesse dia foi desenvolvido o front-end da aplicação, utilizando React e outras bibliotecas:

[Axios](https://github.com/axios/axios) => cliente HTTP, onde é possível fazer request HTTP do nodeJs.

[React Icons](https://react-icons.netlify.com/#/icons/md) => biblioteca que permite a inserção de ícones como componentes dentro da aplicação.

### 4º Dia - Mobile
Nesse dia foi desenvolvido o app mobile, utilizando o React Native e Expo.

### Bibliotecas utilizadas nesse projeto mobile:

[react navigation](https://reactnavigation.org/) => Utilizado para navegar entre as telas.

[expo-constants](https://docs.expo.io/versions/latest/sdk/constants/#constantsstatusbarheight) => Utilizado para estilizar o margin na parte de cima do smartphone para não ficar abaixo da barra de status.

[expo-mail-composer](https://docs.expo.io/versions/latest/sdk/mail-composer/) => Utilizado para a funcionalidade de envio de email para a ONG.

[deep-linking](https://reactnavigation.org/docs/deep-linking/) => Utilizado para acessar o What's app na funcionalidade de entrar em contato com a ONG.

[INTL](https://github.com/andyearnshaw/Intl.js#readme) => Utilizado para formatar os números na UI.

### 5º Dia - Tópicos avançados
Nesse dia adicionamos validação e testes na nossa aplicação:

[celebrate](https://github.com/arb/celebrate) => Utilizado para fazer as validações nos dados enviados ao banco de dados.

[Joi](https://www.npmjs.com/package/joi) => Utilizado em conjunto com o celebrate para a validação dos dados.

[Jest](https://jestjs.io/docs/en/getting-started) => Utilizado para os testes unitários e de integração, implementados aqui

[cross-env](https://github.com/kentcdodds/cross-env#readme) => Utilizado para utilizar variáveis de ambiente para os testes de integração. Veja mais

[supertest](https://github.com/visionmedia/supertest) => Utilizado para os testes com HTTP.

## Agradecimentos
Depois de uma semana intensa, tenho agradecer primeiramente a Deus, pela equipe da Rocketseat pelo empenho, dedicação e disponibilidade demonstradas nesse evento. Foi minha primeira participação e com certeza não será a última. Um agradecimento especial também ao Filipe Deschamps pelos e-mail diários com sua opinião sobre todas as aulas da semana.
