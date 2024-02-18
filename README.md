<p align="center"><a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a></p>

# NestJS Docker Starter Kit
- NestJS v10.x
- TypeScript v5.x
- Postgres v16.x
- Node.js v18.x
- NPM v10.x
- Adminer v4.8.x

# Requirements
- Stable version of [Docker](https://docs.docker.com/engine/install/)
- Compatible version of [Docker Compose](https://docs.docker.com/compose/install/#install-compose)

# How To Deploy

- `docker compose up -d`

# Notes

### App
- URL: http://localhost:3000

### Adminer
- URL: http://localhost:8080
- System: `PostgreSQL`
- Server: `db`
- Username: `refactorian`
- Password: `refactorian`
- Database: `refactorian`

### pgAdmin
- URL: http://localhost:5050
- Email: `admin@admin.com`
- Password: `password`

### Docker compose commands
- Build or rebuild services
    - `docker compose build`
- Create and start containers
    - `docker compose up -d`
- Stop and remove containers, networks
    - `docker compose down`
- Stop all services
    - `docker compose stop`
- Restart service containers
    - `docker compose restart`
- Run a command inside a container
    - `docker compose exec [container] [command]`

# What is Nest?

Nest (NestJS) is a framework for building efficient, scalable [Node.js](https://nodejs.org/) server-side applications. It uses progressive JavaScript, is built with and fully supports [TypeScript](http://www.typescriptlang.org/) (yet still enables developers to code in pure JavaScript) and combines elements of OOP (Object Oriented Programming), FP (Functional Programming), and FRP (Functional Reactive Programming).

Under the hood, Nest makes use of robust HTTP Server frameworks like [Express](https://expressjs.com/) (the default) and optionally can be configured to use [Fastify](https://github.com/fastify/fastify) as well!

Nest provides a level of abstraction above these common Node.js frameworks (Express/Fastify), but also exposes their APIs directly to the developer. This gives developers the freedom to use the myriad of third-party modules which are available for the underlying platform.
