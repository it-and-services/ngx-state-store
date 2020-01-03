# StateStore
Sample application for the ngx-state-store module usage demonstartion.

ngx-state-store simple state management module for the angular applications.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.21.

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

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Publish ngx-state-store module

Execute the following:

         $ make your changes   
         $ increase state-store/projects/ngx-state-store/package.json version
         $ describe the release in the ChangeLog file
         $ npm install 
         $ ng test ngx-state-store
         $ npm run build:release
         $ git add/commit
         $ git tag v0.1.0       # adjust version here
         $ git push origin state-store
         $ git push --tags
         $ npm publish dist/ngx-state-store
