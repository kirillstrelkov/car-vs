# README

This repository contains code for car comparision app.

## Trello board

<https://trello.com/b/mAuFjNDq>

## Initial database

[./db/db.zip](./db/db.zip)

## Prototype

Preview - <https://invis.io/5CXW45SJ2D6>

## Dev

### Prerequisites

Mongodb should be up and running. Use `docker` to start mongodb backend + `MongoDB Compass` for UI.

### Backend

Initialize db:

```bash
cd back
npm run resetdb
```

Start backend:

```bash
cd back
# For debug use:
# npm run start:debug
npm run start:dev
```

#### Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

#### Installation

```bash
$ npm install
```

#### Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

#### Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

### Frontend

Start frontend:

```bash
cd front
ng serve
```

#### Frontend part

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.0.

#### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

#### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

#### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

#### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

#### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

#### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
