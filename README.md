# NODE-JWT-API

  ![Node](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
  ![NPM](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
  ![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
  ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
  ![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)


---

## Resumo

Api criada para autenticar login com JWT 

## Endpoints
---

|Endpoint|Nome|Função| 
|---|---|---|
|/|home|Retorna mensagem de bem vindo
|/auth/register|criar usuario|cria usuario escrito no corpo da requisição via Json, metodo POST
|/user/id|buscar por id|Lista o usuario correspondente ao id informado na URL, metodo GET
|/auth/login|logar|loga o usuario escrito no corpo da requisição via Json, metodo POST

## Executar o projeto localmente
 
### Requisitos

[Git](https://git-scm.com/)

[Node](https://nodejs.org/en/)

[MongoDB Atlas](https://account.mongodb.com/account/login)

Editor de código de sua preferência

### Instalação 

Utilize o Git Clone no repositório em uma pasta de sua escolha

```
$ git clone https://github.com/Gclayton0207/API-NODE-JWT.git
```
Navegue até a pasta do projeto utilizando comando cd

```
$ cd API-NODE-JWT
```
Execute o comando a seguir no terminal para instalar as dependências

```
$ npm install
```

### Configurando ambiente

Para prosseguir com essa etapa é necessário ter cadastro no [MongoDB Atlas](https://account.mongodb.com/account/login).

Após realizar a configuração com Mongo, crie na raiz da pasta do projeto crie um arquivo `.env` seguindo o exemplo enviado no repositorio.

Dentro do arquivo `.env` coloque a sua conexão do MongoDB.

Em seguida utilize o comando para executar o projeto

```
$ npm start
```

## Desenvolvedor

[Giovanni Clayton](https://www.linkedin.com/in/giovanni-clayton/).
