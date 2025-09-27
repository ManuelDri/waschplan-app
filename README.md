<<<<<<< HEAD
# Waschplan-App

Die Waschplan-App ist eine kleine Web-App, mit der man im Mehrfamilienhaus ganz entspannt die Waschmaschine buchen kann. Schluss mit Zetteln an der Tür oder Diskussionen im Treppenhaus – jeder sieht sofort, wann die Maschine frei ist, und kann sich unkompliziert einen Slot reservieren.

## Was die App kann

* Übersichtlicher Wochenplan mit freien und belegten Zeiten
* Slots direkt online reservieren oder wieder freigeben
* Alles läuft in Echtzeit über Firebase – jeder sieht sofort die aktuellen Buchungen

## Technik unter der Haube

* **Frontend:** Angular
* **Backend & Hosting:** Firebase Hosting + Firebase Functions
* **Datenbank:** Cloud Firestore
* **Login:** Firebase Authentication

## Warum?

Weil jeder im Haus waschen muss – und es viel entspannter ist, wenn das Ganze digital und transparent geregelt ist.

## Schnellstart

```bash
git clone https://github.com/<dein-user>/waschplan-app.git
cd waschplan-app
npm install
npm start
```

Deployment auf Firebase:

```bash
firebase deploy
```
=======
# WaschplanApp

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
>>>>>>> f2876cd (chore: initial commit)
