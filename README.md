# NestJS bookmark API tutorial
This is a sample application to store users and bookmarks using NestJS and Prisma.

## Tutorial
https://www.youtube.com/watch?v=GHTA143_b-s

## Technologies

- NestJS
- TypeScript
- Prisma
- PostgreSQL
- Docker
- argon2 (To hash password)
- class-validator (To add validation for each endpoint)
- passport & passport-jwt


## Installation

1. Install NPM modules

```bash
$ yarn install
```

2. Create env files under the root directory
```
touch .env .env.test
```

```
DATABASE_URL="YOUR_DATABASE_URL"
POSTGRES_USER='YOUR_POSTGRES_USER_NAME'
POSTGRES_PASSWORD='YOUR_POSTGRES_PASSWORD'
POSTGRES_DB='YOUR_POSTGRES_DB_NAME'
JWT_SECRET='YOUR_JWT_SECRET'
```

## Running the app

```bash
# Run database 
$ yarn db:dev:restart

# Run application
$ yarn start:dev

# Run Prisma studio
$ npx prisma studio
```

## Test

```bash
# e2e tests
$ yarn run test:e2e
```
