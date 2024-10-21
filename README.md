# Sup de Vinci - Containers module project

*Tested with `rust v1.82.0` et `node 23.0.0`.*

## Development

### API

#### Basics

Use `cargo run` to start the dev environment.

You can also install [cargo-watch](https://crates.io/crates/cargo-watch) to watche over your project's source for changes, and runs Cargo commands when they occur : `cargo-watch -x run`.

#### Using Docker
# Containers Project

## Prérequis
- Docker Desktop
- Cloner le dépôt :
  ```bash
  git clone https://github.com/chrisn237/sdv-m1do-containers-project
  ensuite:
  cd containers_project

## Lancer le projet
Construire et démarrer les conteneurs :
docker-compose up --build

Accéder aux applications :
API : http://localhost:8000
Front-End : http://localhost:3000

Images Docker

API : chrisnnn/containers_project:api_dev
Front-End : chrisnnn/containers_project:web_dev

> TODO

### Web

#### Basics

Use `npm install` to install all dependancies, and `npm run dev` to start the dev environment.

#### Using Docker

> TODO

## Production

### API

#### Basics

Run `cargo build --release` to build and compile the app. This will create an executable in `/target/release/sdv-api`.

#### Using Docker

> TODO

### Web

#### Basics

Run `npm run build` to build the application, and run `npm run start` to start the Node.js server. 

#### Using Docker

> TODO
