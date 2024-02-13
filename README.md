# Api de enquetes

Api de enquetes construida em Node.js e Fastify

## Instalação

Rode este comando para instalar as dependencias necessárias.

```bash
  npm install
```
    
## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env.

`DATABASE_URL`


## Docker

Para subir os containers necessários rode este comando.

```bash
  docker compose up -d
```
    
## Migrations

Para criação das tabelas no banco de dados rode este comando.

```bash
  npx prisma migrate dev
```