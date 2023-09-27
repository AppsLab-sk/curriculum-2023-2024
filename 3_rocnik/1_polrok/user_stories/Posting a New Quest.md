# User Story: Posting a New Quest

## Description

The essence of this user story revolves around enabling users to post a new quest on the QuestOverflow platform. A quest is a complex problem posed by users that require creative solutions from others. By clicking a "Post Quest" button, users should be able to finalize and publish their quest, making it visible to other users for solving.

## Technical Perspective

From a technical standpoint, this user story demands integration between the frontend and the backend. The frontend should feature a user-friendly form for quest creation, while the backend will be responsible for storing this quest in the database. Angular can be used for the frontend form creation, and ASP.NET Core can manage the API endpoint for posting quests. EF Core will be leveraged for database interaction.

## User Perspective

From the user's viewpoint, this feature provides the mechanism for sharing knowledge in the form of quests. Users will anticipate an intuitive and simple UI where they can define the quest, attach any required files or links, and finally, publish it for the community to see and solve.

## Acceptance Criteria

1. A "Post Quest" button must be clearly visible on the user interface.
2. Upon clicking the "Post Quest" button, a form should appear requiring necessary quest details.
3. The form must include fields for quest title, description, complexity level, and any attachments.
4. After finalizing the details, clicking a "Publish" button should post the quest to the platform and be visible to all users.
5. The system should confirm the quest posting via a notification or a redirect to the quest's page.

## What Students Will Learn

1. Front-end development with Angular: Creating forms, buttons, and UI elements.
2. Back-end development with ASP.NET Core: Creating API endpoints.
3. Database Management with EF Core: How to create new records in a database.
4. UI/UX Design: Importance of an intuitive and user-friendly design.
5. End-to-end testing: Ensuring the feature works as expected from start to finish.

## Hints and Suggestions

**Internet Search Suggestions:**

- Angular form creation
- ASP.NET Core API development
- EF Core database interaction

**ChatGPT Prompts:**

- "How to create a form in Angular?"
- "What are best practices for creating API endpoints in ASP.NET Core?"
- "How to integrate Angular with ASP.NET Core?"

**Further Learning:**

- [Official Angular Documentation](https://angular.io/docs)
- [ASP.NET Core Official Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- [Entity Framework Core Documentation](https://docs.microsoft.com/en-us/ef/core/)
