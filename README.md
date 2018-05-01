# Angular 5 Showcase (CLI)- Serve Google Font from Local Asset Directory 


Author: Christian Laboranowitsch
Level: Intermediate
Technologies: Angular 5, angular-cli, SCSS, Boostrap 4, Fontawesome 4.7
Summary: Example setup Bootsrap 4, Local Font, Theming with angular-cli 
Source: <https://github.com/claboran/font-showcase>

## What is it?

The project demonstrates how to setup:
* Bootstrap 4 with angular-cli and SCCS
* Override Bootstrap Defaults -> Custom Theme
* Fontawesome 4.7
* Load Font from local Asset Folder

## Setup 
The Font isn't provided to avoid license problems: 

Download the font from: (https://fonts.google.com/specimen/Noto+Sans?selection.family=Noto+Sans).

Copy `NotooSans-Regular.ttf` from ZIP Archive to `assets/fonts` and your good to go. 

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.2.

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Hints

_variables.scss: Your own theme comes before all Bootstrap defaults `@import '../node_modules/bootstrap/scss/bootstrap';`

