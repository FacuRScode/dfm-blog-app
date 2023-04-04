# DfmBlogApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

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

## Documentación

## Diseño 

Crea el diseño de la web, de cada pagina saca los componentes comunes y separados:
6 Paginas: 1 Home, 2 Single category, 3 single post, 4 terms, 5 about, 6 contact
3 Componentes comunes: 7 Header, 8 Navbar, 9 Footer
3 componentes separados: 10 Suscription form, 11 comment form, 12 comment list

## Crear la app y los componentes

En la consola correr los comandos:
ng new app-name
cd app-name
code . para entrar al IDE

ng serve para correr la app
Borrar el contenido del html de muestra (app.component.html) 

Crear los componentes
ng g c folder/component-name

pages -> paginas
layouts -> componentes comunes
layouts -> componentes separados

## Static: Routing  y navegación (Solo para el diseño)

Dentro de app-routing-module.ts 
En routes
{ path: '', component: name-component },

Escribe en el main html <router-outlet> y prueba las rutas

## Bootstap

npm i bootstrap
Agregrlo a angular.json en css
Volver a correr el serve
ctrl C y ng serve

