# User Story: Quest Posting Confirmation and Listing

## Description

The purpose of this user story is to ensure that a user receives immediate feedback after successfully posting a quest. The user should see a confirmation message and also be able to view their newly posted quest on the quest list page.

## Technical Perspective

From a technical standpoint, this involves front-end and back-end communication. The Angular-based front-end will need to make an HTTP POST request to the ASP.NET Core backend, specifically to the API endpoint responsible for creating new quests. Upon successful creation, the backend should return a confirmation. The front-end will then display a confirmation message and update the quest list by either re-fetching the data or optimistically updating the UI.

## User Perspective

From the user's viewpoint, after posting a new quest, they expect to see a confirmation message like "Your quest has been successfully posted!" and also witness their quest appear in the quest list. This provides the assurance that the operation was successful.

## Acceptance Criteria

1. A confirmation message appears immediately after a quest is successfully posted.
2. The newly posted quest should be visible in the quest list without requiring a page reload.
3. If the quest fails to post, the user should receive an appropriate error message.
4. Backend logs should register the creation of a new quest.

## What Students Will Learn

1. How to make API calls between Angular and ASP.NET Core.
2. Handling API responses and error cases in a user-friendly manner.
3. State management in Angular for dynamically updating UI components.
4. Implementing log mechanisms in ASP.NET Core.

## Hints and Suggestions

**Internet Search Suggestions:**

- Angular HttpClient
- ASP.NET Core Web API
- Optimistic UI updates in Angular

**ChatGPT Prompts:**

- "How to implement API calls between Angular and ASP.NET Core?"
- "What are best practices for displaying confirmation messages in Angular?"
  
**Further Learning:**

- [Angular HttpClient](https://angular.io/guide/http)
- [Create web APIs with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/web-api/?view=aspnetcore-5.0)
