# User Story: Edit Personal Information in User Profile

## Description

The purpose of this user story is to enable registered users to edit their personal information, such as name, email, and profile picture, so that their profiles can reflect up-to-date information.

## Technical Perspective

From a technical standpoint, we'll need to implement an edit functionality on the user profile page. This will involve creating an edit button, which when clicked, will make fields like name and email editable. We'll use Angular forms for the front-end part and an ASP.NET Core API to persist the changes to the database using EF Core.

## User Perspective

From a user’s view, they would expect to navigate to their profile page, click on an "Edit Profile" button, change their details, and save them. Once saved, they expect their profiles to immediately reflect these changes.

## Acceptance Criteria

1. The "Edit Profile" button is visible and functional on the user profile page.
2. Upon clicking the edit button, fields become editable.
3. Saving changes sends a request to the backend and updates the database.
4. After saving, the profile page is refreshed, showing the new, updated information.
5. The process must be secure; only authenticated users can update their profile.

## What Students Will Learn

1. Implementing CRUD operations in ASP.NET Core
2. Using Angular forms for two-way data binding
3. How to design user interfaces that are intuitive and user-friendly
4. Implementing secure API routes for sensitive operations
5. Soft skills: Understanding user needs and translating them into software features

## Hints and Suggestions

**Internet Search Suggestions:**

- Angular Forms Tutorial
- ASP.NET Core CRUD Operations
- Data Validation in EF Core

**ChatGPT Prompts:**

- "How to implement CRUD operations in ASP.NET Core?"
- "How to use Angular forms for two-way data binding?"
- "What are best practices for ensuring secure API routes?"

**Further Learning:**

- [Official ASP.NET Core Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- [Angular Forms Guide](https://angular.io/guide/forms)
