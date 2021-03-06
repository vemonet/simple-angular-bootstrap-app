# AngularExample

Complete angular app with Docker multi stage build using Bootstrap.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.8.

From https://coursetro.com/posts/code/171/Angular-7-Tutorial---Learn-Angular-7-by-Example

Vidéo (50min): https://www.youtube.com/watch?v=5wtnKulcquA

## Docker build

```shell
docker build -t simple-angular-bootstrap-app .
```

## Docker run

```powershell
docker run -it -p 8081:80 simple-angular-bootstrap-app
```

Access at [http://localhost:8081](http://localhost:8081)

## Ng commands

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
