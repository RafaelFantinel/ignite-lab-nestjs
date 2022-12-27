<p align="center">
  <img src="logo.svg" alt="Ignite" width="180"/>
</p>
<p align="center">
     <a href="https://br.linkedin.com/in/rafael-de-oliveira-fantinel-5246a2187">
      <img alt="Rafael Fantinel" src="https://img.shields.io/badge/Rafael%20Fantinel-Linkedin-brightgreen" />
     </a>
     <a href="https://github.com/RafaelFantinel">
       <img alt="License" src=" https://img.shields.io/static/v1?label=RafaelFantinel&message=%20&color=f5f5f5&logo=github">
     </a>
      <img alt="License" src="https://img.shields.io/badge/license-MIT-01B755">
     </a>
   </a>

</p>

## Description

Notifications service developed in rocketseat's ignite-lab

## 🚀 Techs

- Nest.js
- Prisma
- TypeScript
- Jest

## Prerequisites

- [Node LTS](https://nodejs.org/en/)
- [Docker](https://www.docker.com/)
- [Yarn](https://yarnpkg.com/) or NPM

## 🛠 Installation

Clone this project and run with docker

## Running the app

```bash
$ docker compose up -d
```

After uploading the application you will have the following components

- Consumer Nest application running
- Broker Kafka
- Kafka Control center

## Test

```bash
# unit tests
$ yarn test

# e2e tests
$ yarn test:e2e

# test coverage
$ yarn test:cov
```

## License

[MIT licensed](LICENSE).
