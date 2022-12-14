### Top level Architecture

<img width="767" alt="Screenshot 2022-12-27 at 5 15 12 PM" src="https://user-images.githubusercontent.com/32276134/209662064-770331ee-ccec-4627-8fa5-4c56feaa2fb5.png">

## Prerequisites

- Install [docker-compose](https://docs.docker.com/compose/install/)
- Install [postgresql](https://www.postgresql.org/download/)
- Install [Hasura CLI](https://hasura.io/docs/latest/graphql/core/hasura-cli/install-hasura-cli.html)
- Install node and yarn
- cd `middleware` and `npm install`

## Firebase Setup

- We use firebase for authentication
- To run firebase, pass in the `scripts/start --firebase` flag

### Run Project

```
scripts/start
```

### Mobile App.

Create `.env` file and copy content from `dev.example` in App folder

### Code-flow-diagram

checkout [Code flow Diagram Folder](./code-flow-diagram)
