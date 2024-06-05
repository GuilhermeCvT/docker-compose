Configuração de Ambiente com Docker Compose
-----

Este projeto foi criado utilizando o template padrão do NestJS.

Nele, foi utilizado tudo o que foi aprendido no curso DevOps da Rocketset, integrando uma aplicação comum com um banco de dados PostgreSQL.

Para conseguir executar este projeto inteiro:

1. Primeiramente instale todas as dependências:

```
yarn install
```

2. Build o arquivo docker-compose.yaml:

```
docker-compose build
```

3. Por fim, rode os container:

```
docker-compose run -d
```