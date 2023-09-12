# User Story: Direct Access to Quests from Profile History

## Description

This user story aims to add functionality that allows registered users to directly access, review, or revisit quests that they have previously engaged with from their profile history. 

## Technical Perspective

From a technical standpoint, the backend needs to query the database for the user's quest history and display it in their profile. The list of quests will have clickable elements that direct the user to the quest's detail page. This will require integration between the front-end Angular code and the back-end ASP.NET Core services.

## User Perspective

From a user's standpoint, this feature provides an organized and efficient way to review or revisit past quests, making the process more streamlined. A user should expect to see a section in their profile where their past quests are listed, each being clickable to view in detail.

## Acceptance Criteria

1. Users must be able to see a list of quests they have previously engaged with in their profile history.
2. Each quest listed should be clickable.
3. Clicking a quest should navigate to the quest's detail page.
4. The quest history should update in real-time as the user engages with new quests.
5. Data security and integrity must be maintained throughout this feature.

## What Students Will Learn

1. Backend and frontend integration using ASP.NET Core and Angular.
2. Database querying and data retrieval using EF Core.
3. UI/UX considerations for effective user engagement.
4. Best practices in ensuring data integrity and security.

## Hints and Suggestions

**Internet Search Suggestions:**

- ASP.NET Core user profile management
- Angular routing and navigation
- EF Core data retrieval

**ChatGPT Prompts:**

- "How to create a clickable list in Angular?"
- "How to query a user's history with EF Core?"
- "What are best practices for displaying user-specific data securely?"

**Further Learning:**

- [Official documentation for Angular Routing & Navigation](https://angular.io/guide/router)
- [Tutorial on implementing user profile functionalities in ASP.NET Core](https://www.techstrikers.com/Articles/customize-user-profile-info-in-mvc-with-asp.net-identity.php)
