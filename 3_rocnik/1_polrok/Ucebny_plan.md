# Angular a ASP.NET Core

- 1. polrok (16 týždnov, 80 školských hodín)

## Zhrnutie

Tento kurz pokrýva vývoj webových aplikácií s technológiami Angular a ASP.NET Core.

Začína sa základmi týchto technológií a nastavením vývojového prostredia. Študenti sa naučia vytvárať komponenty a databázové štruktúry. Nasledujú implementácie, modelovanie s EF Core, a rozšírenie API pre správu údajov.

Kurz následne pokrýva vylepšenie user experience a efektivity, zavedenie navigácie, zdieľaných služieb a detailného zobrazenia pre úpravu dát.

Potom sú preberané pokročilejšie operácie, ako filtrovanie a triedenie, interakcia používateľa, formátovanie údajov a autentizácia/autorizácia v API, pričom všetko končí prípravou na nasadenie.

V ďalšej fáze sa študenti naučia o vkladaní závislostí, záznamoch, reaktívnych formulároch a stránkovaní. Sú zahrnuté aj komplexnejšie témy, ako sú logovanie, ošetrovanie výnimiek, unit testovanie a asynchrónne spracovanie.

Kurz končí prehľadom učiva, hodnotením práce, retrospektívou a diskusiou o budúcich projektoch. Každá časť má akceptačné kritéria pre overenie porozumenia študentov.

## Lekcie

### Week 1: Setting up the environment

- **Front-end problem**: Understand the basics of Angular and set up a local development environment.
  - **Hint**: Install Node.js and npm. Use Angular CLI to create a new Angular project.
- **Back-end problem**: Understand the basics of ASP.NET Core and set up a local development environment.
  - **Hint**: Install .NET Core SDK. Use .NET CLI to create a new ASP.NET Core project.
- **Lessons**: Angular - Basics, Working with Angular CLI, ASP.NET Core - Basics, Working with .NET CLI
- **Acceptance criteria**: Both Angular and ASP.NET Core environments are set up and ready for development. You are able to create new projects.

### Week 2: Creating components and database structure

- **Front-end problem**: Create the main component of the application: HeroesListComponent and show the list of heroes.
  - **Hint**: Use Angular CLI commands `ng generate component heroes-list`. Understand angular component lifecycle. Use *ngFor directive to display an array of heroes. Use *ngIf to display placeholder if user has no name specified.
- **Back-end problem**: Create the basic structure of the database in MS SQL using EF Core migrations.
  - **Hint**: Define a Hero model and use EF Core tools to create and apply a migration.
- **Lessons**: Angular - Displaying data in the component, EF Core - Migrations
- **Acceptance criteria**: The Angular application can display a list of heroes. The basic structure of the database is ready in MS SQL.

### Week 3: Add Angular material library and Hero model

- **Front-end problem**: Use Angular Material to make heroes-list component look pretty.
  - **Hint**: Use List component to display an array of heroes.
- **Back-end problem**: Create a Hero model and configure EF Core DbContext.
  - **Hint**: Define Hero class with necessary properties and include a `DbSet<Hero>` in your `DbContext` class.
- **Lessons**: Angular - Angular Material, EF Core - Models and DbContext
- **Acceptance criteria**: The Angular application uses Angular Material to display the list of heroes. The Hero model and DbContext are set up in the ASP.NET Core application.

### Week 4: Navigation and API endpoints

- **Front-end problem**: Implement functionality for navigation between different views.
  - **Hint**: Use Angular's Router module to configure and implement navigation.
- **Back-end problem**: Create API endpoints for retrieving and adding heroes.
  - **Hint**: Use ASP.NET Core's Controller classes and action methods to create API endpoints.
- **Lessons**: Angular - Navigation and Routing, ASP.NET Core - Creating APIs
- **Acceptance criteria**: The application allows navigation between different views and is able to add new heroes via API.

### Week 5: Directives and API enhancement

- **Front-end problem**: Work with Angular directives to show and hide elements and display hero data.
  - **Hint**: Use built-in Angular directives like `*ngIf` and `*ngFor` to manipulate the DOM.
- **Back-end problem**: Extend the API endpoints to allow deleting and updating heroes.
  - **Hint**: Add new action methods in your controller to handle HTTP DELETE and PUT requests.
- **Lessons**: Angular - Directives, ASP.NET Core - Extending APIs
- **Acceptance criteria**: The application can display, delete, and update hero details.

### Week 6: Details component and validation

- **Front-end problem**: Create the Detail component, which allows editing the details of a hero.
  - **Hint**: Implement two-way data binding for editable fields in your Detail component.
- **Back-end problem**: Implement validation rules and improve error handling in the API.
  - **Hint**: Use ASP.NET Core's model validation features and exception handling middleware.
- **Lessons**: Angular - Displaying and editing details, ASP.NET Core - Validation and error handling
- **Acceptance criteria**: The application allows editing hero details with validation rules and improved error handling.

### Week 7: Two-way data binding and shared services

- **Front-end problem**: Add the ability to update a model via two-way data binding.
  - **Hint**: Use `[(ngModel)]` directive for two-way data binding in your forms.
- **Back-end problem**: Create and use a shared service to assemble the heroes.
  - **Hint**: Create a service class that uses EF Core to interact with the database and inject it where needed.
- **Lessons**: Angular - Two-way data binding, ASP.NET Core - Shared services
- **Acceptance criteria**: The application allows model updates via two-way data binding and uses shared services for assembling heroes.

### Week 8: Advanced operations and API features

- **Front-end problem**: Implement front-end functionality for advanced operations like filtering and sorting.
  - **Hint**: Use Angular's Pipes and Directives to implement filtering and sorting of heroes on the client-side.
- **Back-end problem**: Create API endpoints for advanced operations like filtering and sorting.
  - **Hint**: Add parameters to your action methods and use LINQ to implement filtering and sorting.
- **Lessons**: Angular - Pipes and Directives, ASP.NET Core - Advanced API features
- **Acceptance criteria**: The application allows advanced operations like filtering and sorting, both on the client-side and via API calls.

### Week 9: User Interaction and Authentication/Authorization

- **Front-end problem**: Allow users to select a hero from the list and edit it in the detail view.
  - **Hint**: Use property binding to bind a selected hero to the detail view.
- **Back-end problem**: Implement authentication and authorization in the API.
  - **Hint**: Use ASP.NET Identity to add authentication and authorization. Configure and apply policies for controlling access to API endpoints.
- **Lessons**: Angular - User interaction, ASP.NET Core - Authentication and Authorization
- **Acceptance criteria**: The application allows users to select and edit a hero. The API has authentication and authorization set up, controlling who can access and modify data.

### Week 10: Formatting with pipes and deployment

- **Front-end problem**: Format data using pipes.
  - **Hint**: Use built-in Angular pipes and/or create custom pipes for data transformation.
- **Back-end problem**: Finish testing and debugging the API, prepare for deployment.
- **Hint**: Use unit testing and integration testing for the API. Prepare the application for deployment (environment variables, deployment scripts, etc.)
- **Lessons**: Angular - Pipes, ASP.NET Core - Preparation for deployment
- **Acceptance criteria**: The application is complete with data formatting, the database is optimized, and it's ready for deployment.

### Week 11: Dependency Injection and Logging

- **Front-end problem**: Understand and use dependency injection in Angular.
  - **Hint**: Inject services into components using Angular's dependency injection system.
- **Back-end problem**: Implement logging in your ASP.NET Core application.
  - **Hint**: Use built-in or third-party logging providers to log important information about your application's behavior.
- **Lessons**: Angular - Dependency Injection, ASP.NET Core - Logging
- **Acceptance criteria**: Dependency injection is used in the Angular application. Logging is set up in the ASP.NET Core application.

### Week 12: Reactive Forms and Pagination (BONUS)

- **Front-end problem**: Improve your forms by switching from template-driven to reactive forms.
  - **Hint**: Use Angular's `ReactiveFormsModule` and related classes like `FormGroup` and `FormControl`.
- **Back-end problem**: Implement server-side pagination for the heroes list.
  - **Hint**: Use query parameters to get a specific page of data from your API endpoints.
- **Lessons**: Angular - Reactive Forms, ASP.NET Core - Pagination
- **Acceptance criteria**: The application uses reactive forms. The API supports pagination.

### Week 13: Routing Guards and Exception Handling (BONUS)

- **Front-end problem**: Implement routing guards to protect certain routes.
  - **Hint**: Use Angular's `CanActivate` or `CanDeactivate` guards.
- **Back-end problem**: Implement global exception handling in your ASP.NET Core application.
  - **Hint**: Use middleware to handle exceptions globally and return appropriate HTTP responses.
- **Lessons**: Angular - Routing Guards, ASP.NET Core - Exception Handling
- **Acceptance criteria**: Certain routes in the Angular application are protected by routing guards. Exceptions are handled globally in the ASP.NET Core application.

### Week 14: Testing and Optimizing API Calls (BONUS)

- **Front-end problem**: Implement unit testing for your Angular components and services.
  - **Hint**: Use Angular's testing framework and Jasmine to create and run tests for your components and services.
- **Back-end problem**: Optimize your API calls.
  - **Hint**: Use features like caching, compression, or batching to improve your API's performance.
- **Lessons**: Angular - Testing, ASP.NET Core - Optimizing API Calls
- **Acceptance criteria**: The application has unit tests for its components and services. API calls are optimized.

### Week 15: Async Pipe and Asynchronous Processing (BONUS)

- **Front-end problem**: Use async pipe to subscribe to Observables from the template.
  - **Hint**: Use Angular's `async` pipe to subscribe to Observables and automatically update the view.
- **Back-end problem**: Implement asynchronous processing in your ASP.NET Core application.
  - **Hint**: Use async/await keywords and asynchronous versions of EF Core methods.
- **Lessons**: Angular - Async Pipe, ASP.NET Core - Asynchronous Processing
- **Acceptance criteria**: Async pipe is used in the Angular application. The ASP.NET Core application supports asynchronous processing.

### Week 16: Recap, Evaluation, Retrospective, and Proposals for Future Projects

- **Front-end review**: Recap the main topics covered throughout the course and evaluate the Angular projects completed by students.
  - **Hint**: Review Angular topics including components, directives, routing, services, forms, HttpClient, and more. Evaluate students' projects and provide constructive feedback.
- **Back-end review**: Recap the main topics covered in the ASP.NET Core curriculum and evaluate the projects completed by students.
  - **Hint**: Review ASP.NET Core topics including models, DbContext, migrations, API endpoints, authentication, exception handling, logging, and more. Evaluate students' projects and provide constructive feedback.
- **Retrospective and proposals**: Conduct a course retrospective to discuss what went well and what could be improved. Discuss potential future projects that students can work on to continue their learning.
  - **Hint**: Facilitate a discussion on the course content, teaching methods, and student projects. Discuss new project ideas that incorporate advanced topics or integrate with other technologies.
- **Lessons**: Review of Angular and ASP.NET Core, Evaluation of student work, Course retrospective, Discussion of future projects
- **Acceptance criteria**: Students demonstrate a thorough understanding of the course content. Feedback is collected and potential future projects are identified.
