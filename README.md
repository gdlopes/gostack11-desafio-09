<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 09: Relacionamentos com banco de dados no Node.js
</h3>

---

## :rocket: Sobre o desafio

Detalhes do desafio: https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-database-relations/README.md

## :computer: Tecnologias utilizadas

- [Node](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [typescript](https://www.typescriptlang.org/)
- [ts-node-dev](https://www.npmjs.com/package/ts-node-dev)
- [ts-jest](https://www.npmjs.com/package/ts-jest)
- [uuidv4](https://www.npmjs.com/package/uuidv4)
- [jest](https://jestjs.io/docs/en/getting-started.html)
- [supertest](https://www.npmjs.com/package/supertest)
- [csv-parse](https://www.npmjs.com/package/csv-parse)

## :warning: Pré-requisitos

- [git](https://git-scm.com/)
- [insomnia](https://insomnia.rest/)
- [docker](https://www.docker.com/)

## :information_source: Instruções para rodar o projeto

Primeiro é necessário criar um banco de dados para conseguir utilizar a aplicação, você pode fazer isso usando o docker, desta forma:

```bash
$ docker run --name gostack_desafio09_tests -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

É possível criar utilizando outras credenciais, caso mude, lembre-se de alterar no [arquivo de configuração do typeorm](https://github.com/gdlopes/gostack11-desafio-09/blob/master/ormconfig.json).

Feito isso, podemos seguir.

```bash
# Clonando o repositório
$ git clone https://github.com/gdlopes/gostack11-desafio-09.git

# Navegando para a pasta do projeto
$ cd gostack11-desafio-09

# Instalando as dependências
$ yarn

# Rodando a aplicação
$ yarn dev:server
```

### :pencil2: Para rodar os testes, basta utilizar o seguinte comando:

```bash
  # Rodando os testes
  $ yarn test
```

## :boom: Agora, utilize o [Insomnia](https://insomnia.rest/) para ver tudo funcionando :)

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=GoStack%20-%20Desafio%2009&uri=https%3A%2F%2Fgithub.com%2Fgdlopes%2Fgostack11-desafio-09%2Fblob%2Fmaster%2FInsomnia_2020-07-30.json)

### Thats it ! :wave:

---

by Gustavo Lopes :tada:
