## Image Cropping Tool [Provisional]

> This single page application is built with Angular, NodeJS and Jimp and is hosted on Firebase

This tool uses:

- [jimp](https://www.npmjs.com/package/jimp)

### TODO:

- Create an angular project that uploads an image into Firebase
- The angular frontend will be capable of creating a select area to generate cropping data
- The angular frontend saves the cropping data along with the url of the image stored
- The angular project sends this data to node backend
- The node backend are actually firebase functions
- The node backend saves a cropped image into firebase
- The node backend sends the url back to the angular via observable
- The angular frontend lets the user download the image
- The image name is customized to prevent duplication or obfuscation

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.1.

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
