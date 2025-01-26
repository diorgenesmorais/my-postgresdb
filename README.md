# Cria um container com o Postgres

Este projeto configura e executa um container Docker com PostgreSQL.

## Pré-requisitos

- Docker
- Docker Compose

## Configuração

1. Copie o arquivo de exemplo `.env.example` para `.env`:

    ```bash
    cp .env.example .env
    ```

2. Edite o arquivo `.env` e configure as variáveis de ambiente `POSTGRES_DB`, `POSTGRES_USER` e `POSTGRES_PASSWORD`.

## Executando o container

Para iniciar o container PostgreSQL, execute o comando:

```bash
docker-compose up -d
```

## Parando o container

Para parar o container PostgreSQL, execute o comando:

```bash
docker-compose down
```

## Authors

[**Diorgenes Morais**](https://github.com/diorgenesmorais)