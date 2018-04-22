# Junglee Games Assignment

## Overview

This application displays all available vouchers as well user can add voucher himself. After selecting the voucher, user has to select pay mode and do the payment. After successfully payment, user will get confirmation message.

## Prerequisites
### AngularJS 5
I've used Angular 5 library, because of Application architecture is in AngularJS.

### NPM
Angular and it's dependancies has installed using node package manager.

### Karma and Jasmine
Used Karma and Jasmine for unit testing.
- You can run the server unit testing via `npm test`

### Node.js
I've used node to run Karma unit testing. Using Karma-Jasmine for unit testing here.
- Install the tool dependencies ('npm install').
-


## Workings of the application

- The application filesystem layout structure is based on the single page application.
- There is no dynamic backend (no application server) for this application. We have used a static JSON file to read
  data.

### Installing dependencies

The application relies upon node.js tools.  You can
install dependencies by running:

```
npm install -g @angular/cli
npm install

```

### Running the app during development

- You can run the server using command `ng serve --open`. It will automatically open your application in browser.
- Or you can also redirect by browser to `http://localhost:4200/` to see the app running in your browser.

## Application Directory Layout

    e2e                 --> Inside e2e/ live the end-to-end tests. They shouldn't be inside src/ because e2e      tests are really a separate app that just so happens to test your main app. That's also why they have their own tsconfig.e2e.json.

    node_modules        --> Node.js creates this folder and puts all third party modules listed in package.json inside of it.

    src                 --> All Angular components, templates, styles, images, and anything else your app needs go here. Any files outside of this folder are meant to support building your app.

    .angular-cli.json   --> Configuration for Angular CLI. In this file you can set several defaults and also configure what files are included when your project is built. Check out the official documentation if you want to know more.

    .editorconfig       --> Simple configuration for your editor to make sure everyone that uses your project has the same basic configuration. Most editors support an .editorconfig file.

    .gitignore          --> Git configuration to make sure autogenerated files are not commited to source control.

    karma.conf.js       --> Unit test configuration for the Karma test runner, used when running ng test.

    package.json        --> npm configuration listing the third party packages of application.

    protractor.conf.js  --> End-to-end test configuration for Protractor, used when running ng e2e.

    tsconfig.json       --> TypeScript compiler configuration.

    tslint.json         --> Linting configuration for TSLint together with Codelyzer, used when running ng lint. Linting helps keep your code style consistent.


## Contact Me
- Dheeraj Jaiswal
- jdheeraj32@yahoo.com
- 9810550702
