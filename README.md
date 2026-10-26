# DemoApp

DemoApp is a starter single-page application built with Angular 22. It currently
shows Angular's getting-started welcome page, including links to Angular
learning resources and developer tools. It is a foundation for adding
application-specific pages and features.

## Features

- Angular standalone root component
- Angular Router configured and ready for routes
- Angular starter welcome screen
- Unit tests with Vitest

> The router currently has no application-specific routes, and the project does
> not yet include a backend or domain-specific features.

## Requirements

- Node.js and npm

## Getting started

Clone the repository and install the dependencies:

```bash
git clone https://github.com/Kartikunde/Angular-Folder.git
cd Angular-Folder
npm ci
```

Start the local development server:

```bash
npm start
```

Open [http://localhost:4200/](http://localhost:4200/) in your browser. The
development server rebuilds the app when source files change.

## Available commands

| Command | Description |
| --- | --- |
| `npm start` | Start the Angular development server |
| `npm run build` | Create an optimized production build in `dist/` |
| `npm test` | Run the unit tests |
| `npm run watch` | Rebuild on source changes using the development configuration |

## Project structure

| File | Purpose |
| --- | --- |
| `main.ts` | Bootstraps the Angular application |
| `app.ts` | Defines the root application component |
| `app.html` | Contains the welcome page template |
| `app.config.ts` | Configures application-wide providers |
| `app.routes.ts` | Defines the application routes |
| `app.spec.ts` | Tests the root component and welcome heading |
| `angular.json` | Angular CLI build, serve, and test configuration |

## Technology

- Angular 22
- TypeScript
- RxJS
- Vitest

For Angular documentation, see the [Angular documentation](https://angular.dev/).
