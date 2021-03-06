# Angular Material Starter

This is a starter template for angular with angular material as design components for angular

## Stack

- angular cli
- angular 5
- angular material
- angular flex-layout
- parse-server (to mock backend api)

## Features
- Progressive Web App with angular service worker
- SPA Application Template
- Header with menu / theme change / profile
- Collapsible side menu for navigation
- Routing module organized with pages
- Angular Material theming with live theme change
- Highly responsive with flex-layout
- Easy JWT authentication & mocked backend rest API using parse-server (https://github.com/parse-community/parse-server)


## Pre-requisites
- nodejs > 8
- yarn > 1.5
- angular cli > 1.7

## Installation
```
git clone https://github.com/abariatti/angular-material-starter
yarn install 
```

## Run
Without authentication and backend api 
```bash
yarn start 
```
With mocked backend api and authentication (parse-server)
```bash
# you might need elevated privileges to run this properly
yarn start:server
```

Browse: 
http://localhost:4200/

## Angular CLI

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
