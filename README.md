# NgDocker(

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.2.

## Development server

Run `ng serve` for a dev server. 

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Build a Custom Docker Image

Run `docker build -t ngcode . -f Dockerfile`

## Check the image using docker run command 

* Run `docker images` command.
* Run `docker run -d -p 80:80 -- name ngcode ngcode` command.
