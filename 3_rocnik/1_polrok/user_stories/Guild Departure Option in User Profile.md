# User Story: Guild Departure Option in User Profile

## Description

The primary aim of this user story is to allow registered users the freedom to leave their current guild through an option in their profile settings. This gives users the flexibility to join new guilds if they wish to align with a different set of quest solvers.

## Technical Perspective

From a technical standpoint, this feature will necessitate the following:
- Backend logic to remove the user's association from the guild in the database.
- Update the Guild's member count and re-allocate any guild-specific roles or responsibilities.
- A frontend UI update in the user's profile to include an option to 'Leave Guild.'
- Use Angular for the frontend change, and ASP.NET Core with EF Core for backend and database management.

## User Perspective

Upon implementation, users would expect to see a clear, user-friendly option within their profile settings to leave a guild. A confirmation dialog should appear to ensure the user is making a deliberate choice. Post-confirmation, they would expect to be removed from their current guild and be able to join a new one.

## Acceptance Criteria

1. The 'Leave Guild' option should be clearly visible in the user profile settings.
2. Upon clicking 'Leave Guild,' a confirmation dialog should appear.
3. After confirming, the user is removed from the current guild in the system.
4. The guild's member count should be decremented by one.
5. The user should receive a notification or alert confirming their departure from the guild.

## What Students Will Learn

1. Backend logic manipulation with ASP.NET Core and EF Core.
2. Frontend design using Angular, focusing on user experience.
3. Database relations and updates, particularly foreign key constraints.
4. Implementation of confirmation dialogs and notifications.
  
## Hints and Suggestions

**Internet Search Suggestions:**

- Remove item from Angular list
- ASP.NET Core delete foreign key constraint
- UI/UX best practices for settings menu

**ChatGPT Prompts:**

- "How to implement a confirmation dialog in Angular?"
- "What are best practices for updating database relationships in EF Core?"

**Further Learning:**

- [ASP.NET Core Documentation for managing database relationships](https://learn.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/work-with-data-in-asp-net-core-apps)
- [Best Practices for Designing UI Menus](https://app.uxcel.com/courses/ui-components-n-patterns/anatomy-ii-502)
