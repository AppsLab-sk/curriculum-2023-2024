# User Story: Quest Title Entry in Creation Form

## Description

The purpose of this user story is to allow users to input a title when creating a new quest. The title serves as a brief explanation of what the quest is about, thereby guiding potential solvers to understand its context quickly.

## Technical Perspective

From a technical standpoint, a text input field will be added to the quest creation form. This will require modifications in the front-end (Angular) to introduce the new form control and also backend adjustments (ASP.NET Core) to accept, validate, and store this new piece of information in the database (EF Core).

## User Perspective

The user will expect to see a text input box under the section of 'Quest Creation' where they can type in the title for the new quest. This provides an immediate and accessible way to clarify the nature of the quest they are posting.

## Acceptance Criteria

1. A text input box for the quest title should appear on the quest creation form.
2. The title should be mandatory; the form cannot be submitted without it.
3. The title should be limited to a certain number of characters to ensure it stays brief.
4. The title should be stored in the database and be visible when viewing the quest details.

## What Students Will Learn

1. Front-end development: Adding and styling form controls in Angular.
2. Back-end development: Modifying the API to accept and store new data elements in ASP.NET Core.
3. Database management: How to alter database schema to include a new field with EF Core.
4. User Experience: The importance of intuitive design and meaningful placeholders.

## Hints and Suggestions

**Internet Search Suggestions:**

- Angular form control creation
- ASP.NET Core model validation
- EF Core database schema migration

**ChatGPT Prompts:**

- "How to implement a mandatory field in an Angular form?"
- "What are the best practices for database schema modification in EF Core?"
  
**Further Learning:**

- [Angular Forms Documentation](https://angular.io/guide/forms-overview)
- [EF Core Migrations](https://docs.microsoft.com/en-us/ef/core/managing-schemas/migrations/)
