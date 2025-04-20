# Simple Counter

<img width="956" alt="image" src="https://github.com/user-attachments/assets/61215a2f-dc91-406b-b6a7-81d6dbb4e13e" />


( Note to self : Project name under /dist folder is untitled3 so please be cautious)

(Commands I use to push and deploy here , in order) :  
git init
git remote add origin https://github.com/deepshikha3/counter.git         
 git add .
git commit -m "Initial commit to Git"
  git push -u origin master
 npm install -g angular-cli-ghpages
 ng build --base-href /counter/
 npx angular-cli-ghpages --dir=dist/untitled3

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.8.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
