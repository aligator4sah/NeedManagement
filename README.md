# NeedManagement

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Main Functionality

1. Display the need requests with general fields in one table (MVP  1)
2. Display the help offerings with genetal fields in one table (MVP - 1)
3. Show request detail infomation when click the row (MVP - 1)
4. Sort the requests information according to priority/created time (MVP - 1)
5. List the requests accrording to category
6. Track requests status - new / in progress / completed (MVP - 1)
7. Match the requests with possible help offerings (button after each row)
8. Grab data from Google form/response and refresh per hour (MVP - 2)
9. Send notification (email / text) to people who offer help / needs help

## Architecture design

Front-end: Angular + Material Design
Back-end: Spring 
Database: PostgresSQL
Cross-platform: React Native
Deployment: Heroku / AWS