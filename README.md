# Lisa Angular Material JSON CRUD APP

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.1 and [JSON Server](https://www.npmjs.com/package/json-server).

## Development server
Please install node_modules by using the CLI in your project by typing in `npm install` or, `npm i`.
Also you will need to ensure that you have navigated into the main folder of your project with the CLI or terminal inside the project to ensure that you install JSON Server by entering `npm i json-server` into the CLI while inside your project. To ensure that Angular Material is installed, next type `ng add @angular/material` into the project via your CLI.

You will then need to open two terminals or CLI windows one to run the serverless JSON database file named db.json. In one terminal or session of CLI you must again be inside the main project folder. Type in the commad `npm install -g json-server` to ensure that the JSON Server is fully installed then type in the next command `json-server --watch db.json` this will spin up the serverless JSON database. You will be given a link of the resources to view you may open this link in a new window if prefered (http://localhost:3000/employees) you will then be able too see all entries for this project.

In the second CLI terminal window within your project's main folder run the command `ng serve` to see the project at (http://localhost:4200/). The application will automatically reload if you change any of the source files. You will also get a link to see the data that JSON is using in the background you have entered.

Please note that both terminals or instantiations of JSON Serverless database and the Angular CLI must remain open while working on this project so that you can CREATE, READ, UPDATE or DELETE items within your project.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
