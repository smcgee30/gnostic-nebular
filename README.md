# Angular5GraphqlStarter

This project is created as a security example using tools and is used in the ISO DevSecOps group.  Instead of making a huge readme, I'll put information here:  http://docs.turner.com/display/ISO/Use+of+Angular-GraphQL+Starter


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.  The port can be changed. 

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. I've put in 3 environment variables.  You'll want to change the test and prod URLS in the environment ts files before you use those.

ng build --env=dev
ng build --env=test
ng build --env=prod  (This also optimizes your build.)

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
