<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/rmoise/myFlix-Angular-client">
    <img src="img/logo-readme.png" alt="Logo" width="80" height="80">
  </a>

  <h1 align="center">myFlix - Angular App. Technical Case Study</h1>

  <p align="center">
    <a href="https://rmoise.github.io/myFlix-Angular-client/welcome">View Demo</a>
    ·
    <a href="https://github.com/rmoise/myFlix-Angular-client/issues">Report Bug</a>
    ·
    <a href="https://github.com/rmoise/myFlix-Angular-client/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#objective">Objective</a>
        <li><a href="#context">Context</a></li>
    </li>
    <li><a href="#the-5-ws">The 5 Ws</a></li>
       <li><a href="#user-stories">User Stories</a></li>
        <ul>
    </li>
    </ul>
    <li><a href="#key-features">Key Features</a>
    <li><a href="#technical-requirements">Technical Requirements</a>
    <li><a href="#application-documentation">Application Documentation</a>
    <li><a href="#project-deliverables-in-story-points">Project Deliverables in Story Points</a>
    <li><a href="#development-server">Development Server</a>
    <li><a href="#code-scaffolding">Code Scaffolding</a>
    <li><a href="#build">Build</a>
    <li><a href="#running-unit-tests">Running Unit Tests</a>
    <li><a href="#running-end-to-end-tests">Running End-to-End Tests</a>
     <li><a href="#further-help">Further Help</a>
    <li><a href="#built-with">Built With</a></li>
  </ol>
</details>

## Objective

Using Angular, build the client-side for an application called myFlix based on its existing server-side code (REST API and database), with supporting documentation.

[![myFlix Angular client screenshot][product-screenshot]](https://rmoise.github.io/myFlix-Angular-client/movies)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Context

Angular is a trendy framework used for a wide range of mobile and desktop applications. It's particularly well-suited to large projects and projects requiring a complex user interface because it comes with a variety of built-in modules and services.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## The 5 W's

- Who? — The users of the myFlix movie app and codebase, including other developers and designers.
- What? — A single-page, responsive movie app built with Angular, routing, and several interface views. The client-side developed in this project supports the existing server-side from [myFlix API](https://github.com/rmoise/myFlix_api) by facilitating user requests and rendering the response from the server-side via several different interface views. The app includes relevant documentation and handoff deliverables, including a [Kanban board](https://app.ora.pm/p/94849f247f3745e483ddd753237fb4f1?v=0&t=k) containing user stories and story points
- When? — Users should be able to use the app whenever they want to read information about different movies or update their user information
- Where? — The app is hosted online. It is responsive and can therefore be used anywhere and on any device, giving all users an equal experience
- Why? — Movie enthusiasts should be able to access information about different movies, directors, and genres whenever they want. The app demonstrates my Angular skills and ability to create straightforward documentation for other developers and employers.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## User Stories

- As a user, I should be able to receive information on movies, directors, and genres so that I can learn more about movies I've watched or am interested in
- As a user, I should be able to create a profile so I can save data about my favorite movies.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Key Features

- The app should display a welcome view where users will be able to either login or register an account.
- Once authenticated, the user should now view all movies
- Upon clicking on a particular movie, users are taken to a single movie view, where additional movie details are displayed. The single movie view will contain the following additional features:
  - A view details button, when clicked, takes a user to the director view​, where details about the director of that particular movie are displayed
  - A view details button, when clicked, takes a user to the ​genre view​, where details about that particular genre of the movie are displayed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Technical Requirements

- The application must use the [myFlix API](https://github.com/rmoise/myFlix_api) as Back-End
- The application must be written in Angular (version 9 or later)
- The application requires the latest version of Node.js and npm package
- The application must contain user registration and login forms
- The application must be designed using Angular Material UI
- The application's codebase must be documented using TypeDoc
- The project must be hosted on GitHub Pages.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## [Application Documentation](https://github.com/rmoise/myFlix-Angular-client/tree/master/docs)

Documentation was generated via TypeDoc.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Project Deliverables in Story Points

- Main View Page -> 5 story points
- Profile View Page -> 5 story points
- Registration Page -> 2 story points
- Login View Page -> 3 story points
- Movie View Page -> 5 story points
- Movie Card -> 3 story points
- Genre View Page -> 2 story points
- Director View Page -> 2 story points

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Development Server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Code Scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Running Unit Tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Running End-to-End Tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Further Help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

<!-- prettier-ignore -->
* [![Angular][angular]][angular-url]
* [![Material][material]][material-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>

[angular]: https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white
[angular-url]: https://angular.io/
[material]: https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white
[material-url]: https://material.angular.io/

[product-screenshot]: img/myFlix-Angular-app-screenshot.png
