# CampusUniverse Backend

## Description

CampusUniverse backend

## Apps

It include the following applications:

1. **gateway:** Entry point into the backend.

## Todos

- [ ] Authentication (OAuth)

## Project setup

```bash
$ pnpm install
```

## Compile and run the project

```bash
# development
$ pnpm run start gateway

# watch mode
$ pnpm run dev gateway

# production mode
$ pnpm run start:prod gateway
```

## Run tests

```bash
# unit tests
$ pnpm run test gateway

# e2e tests
$ pnpm run test:e2e gateway

# test coverage
$ pnpm run test:cov gateway
```

## Deployment

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:

```bash
$ pnpm install -g mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.
