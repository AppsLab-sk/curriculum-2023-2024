# User Story: View Posted and Solved Quests

## Description

This user story aims to provide registered users with a feature that allows them to see a list of all the quests they have posted or solved. This feature is vital for users to keep track of their contributions and the problems they have addressed.

## Technical Perspective

From a technical standpoint, this functionality involves:
- Extending the backend API to support retrieval of user-specific quest data (both posted and solved).
- Designing and implementing a new component in Angular for the frontend to display this data in a list format.
- Employing EF Core to manage the database queries related to this feature.

## User Perspective

From the end-user's standpoint, a new tab or section should be visible within the dashboard area, named something like "My Quests". Clicking on it should display a list of quests they have either posted or solved. This list could also allow for sorting and filtering for ease of use.

## Acceptance Criteria

1. A new tab or section is introduced in the user's dashboard specifically for viewing posted and solved quests.
2. This section will display a list of quests the user has posted or solved.
3. Users should be able to sort this list based on various parameters like date posted, solved status, etc.
4. The information should update in real-time, meaning if a quest is newly posted or recently solved, it should appear on this list without requiring a page refresh.

## What Students Will Learn

1. How to extend an ASP.NET Core API to handle more complex queries.
2. Design and implementation of new Angular components.
3. Efficient use of EF Core for database operations.
4. User interface design considerations for better UX.

## Hints and Suggestions

**Internet Search Suggestions:**

- Angular component design patterns
- ASP.NET Core API best practices
- EF Core complex queries

**ChatGPT Prompts:**

- "How to design an efficient list view in Angular?"
- "What are the best practices for extending an ASP.NET Core API?"
- "How to use EF Core for complex database queries?"

**Further Learning:**

- [ASP.NET Core Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-5.0)
- [Angular Component Design Tutorial](https://angular.io/guide/component-overview)
- [EF Core Documentation](https://docs.microsoft.com/en-us/ef/core/)