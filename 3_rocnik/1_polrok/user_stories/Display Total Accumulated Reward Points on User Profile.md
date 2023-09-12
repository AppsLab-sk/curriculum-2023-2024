# User Story: Display Total Accumulated Reward Points on User Profile

## Description

The purpose of this user story is to provide registered users the ability to see their total accumulated reward points displayed on their user profile. This will allow users to gauge their progress and understand how close they are to leveling up.

## Technical Perspective

The back-end needs to query the database to fetch the total reward points associated with the logged-in user. This information will be exposed through an API endpoint using ASP.NET Core. On the front-end, Angular will consume this API to display the points in the user profile section.

## User Perspective

Users expect to see a section or an element in their profile page where their total accumulated reward points are displayed. The display should update in real-time or at least refresh when the page is reloaded, reflecting any new points gained.

## Acceptance Criteria

1. Back-end API successfully retrieves the total reward points for the logged-in user.
2. Front-end fetches this data and displays it in the profile page.
3. The displayed reward points must be accurate and up-to-date.
4. There should be proper handling and display of errors, such as a message if the server fails to provide the data.

## What Students Will Learn

1. How to fetch data from a database using EF Core.
2. How to expose data through an API using ASP.NET Core.
3. Consuming APIs using Angular services.
4. User Interface (UI) design principles for intuitive display of key information.
  
## Hints and Suggestions

**Internet Search Suggestions:**

- Fetching data with EF Core
- Creating API with ASP.NET Core
- Consuming API in Angular

**ChatGPT Prompts:**

- "How to fetch data from a database in ASP.NET Core?"
- "How to create an API endpoint in ASP.NET Core?"
- "How to consume an API using Angular?"

**Further Learning:**

- [Official documentation of Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/)
- [Building APIs with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/web-api/?view=aspnetcore-5.0)
- [Angular API consumption tutorial](https://angular.io/tutorial/toh-pt6)
