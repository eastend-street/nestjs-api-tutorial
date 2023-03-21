# NestJS bookmark API tutorial
This is a sample application to store users and bookmarks using NestJS and Prisma.

## Tutorial
https://www.youtube.com/watch?v=GHTA143_b-s

## Technologies

- NestJS
- TypeScript
- Prisma
- Docker
- argon2 (To hash password)
- class-validator (To add validation for each endpoint)
- passport & passport-jwt


## Installation

```bash
$ yarn install
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
