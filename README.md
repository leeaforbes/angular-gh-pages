```
npm install -g @angular/cli
ng new angular-gh-pages

ng build --output-path docs --base-href /your_project_name/
ng build --output-path docs --base-href /angular-gh-pages/

git add .
git commit -m "first commit"
git remote add origin <your-github-repo-link>
git remote add origin https://github.com/leeaforbes/angular-gh-pages
git push

ng add angular-cli-ghpages
ng deploy --base-href=/<your-repo-name>/
ng deploy --base-href=/angular-gh-pages/

Git repo > Settings > Pages
Set branch to gh-pages (created and pushed by above)

Visit your Angular Github Pages


-------------------------


New changes?
ng build --output-path docs --base-href /angular-gh-pages/
git add .
git commit -m "second commit"
git push
ng build --output-path docs --base-href /angular-gh-pages/
ng deploy

```







# AngularGhPages

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 21.1.3.

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

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

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
