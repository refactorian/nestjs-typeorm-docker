<p align="center"><a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a></p>

# NestJS Docker Starter Kit
- NestJS v10.x
- TypeScript v5.x
- MariaDB v10.11.x (default)
- MySQL v8.1.x
- Postgres v16.x
- pgAdmin v4.x
- Adminer v4.8.x
- Node.js v18.x
- NPM v10.x

# Requirements
- Stable version of [Docker](https://docs.docker.com/engine/install/)
- Compatible version of [Docker Compose](https://docs.docker.com/compose/install/#install-compose)

# How To Deploy

- `docker compose up -d`

# Notes

### App
- URL: http://localhost:3000

### phpMyAdmin
- URL: http://localhost:8080
- Server: `db`
- Username: `refactorian`
- Password: `refactorian`
- Database: `refactorian`

### Adminer
- URL: http://localhost:9090
- Server: `db`
- Username: `refactorian`
- Password: `refactorian`
- Database: `refactorian`

<!-- ### Adminer
- URL: http://localhost:9090
- System: `PostgreSQL`
- Server: `db`
- Username: `refactorian`
- Password: `refactorian`
- Database: `refactorian`

### pgAdmin
- URL: http://localhost:5050
- Email: `admin@admin.com`
- Password: `password` -->

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
