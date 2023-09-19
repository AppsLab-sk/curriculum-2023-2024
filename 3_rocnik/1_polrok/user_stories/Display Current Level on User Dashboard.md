# User Story: Display Current Level on User Dashboard

## Description

The purpose of this user story is to allow registered users to easily see their current level displayed prominently on their profile. This serves as a real-time indicator of the user's progress within the QuestOverflow platform.

## Technical Perspective

To achieve this, we'll need to make updates on both the backend and frontend. On the backend, using ASP.NET Core, we can expose an API endpoint that fetches the user's current level based on their ID. On the frontend, using Angular, we can call this API and display the level in a visually pleasing manner on the user's dashboard page.

## User Perspective

Upon logging in and navigating to dashboard, the user expects to see their current level displayed. This informs them of their current standing within the system, influencing decisions such as which quests to tackle or whether they should strive to level up.

## Acceptance Criteria

1. The user's level must be prominently displayed on their dashboard page.
2. The level displayed must be up-to-date, reflecting any recent quest completions or other actions that would affect their level.
3. The system should handle cases where the level data could not be fetched, by showing a relevant error message.
4. The design should be responsive to fit different screen sizes.

## What Students Will Learn

1. How to create an API endpoint in ASP.NET Core that fetches specific user information.
2. How to make API calls from an Angular frontend to a .NET backend.
3. Working with user-specific data and managing state.
4. UI/UX considerations for effective information display.

## Hints and Suggestions

**Internet Search Suggestions:**

- Fetch user data with ASP.NET Core
- Display dynamic data in Angular
- Responsive design with Angular
- Applying Migrations with Entity Framework

**ChatGPT Prompts:**

- "How to create an API endpoint for user data in ASP.NET Core?"
- "How to fetch and display dynamic data in Angular?"
- "What are the best practices for displaying user-specific information on a web page?"
- "How to add properties to existing model class and run EF migration scripts to apply them?"

**Further Learning:**

- ASP.NET Core official documentation for creating API endpoints
- Angular documentation on how to make HTTP requests
- A relevant tutorial on managing state and user data within an Angular application
- Community forums like Stack Overflow for problem-solving and best practices
