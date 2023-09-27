# User Story: Quest Complexity Level Selection

## Description

The purpose of this user story is to allow quest posters to set a predefined complexity level for their quests. By doing so, they provide potential solvers with an idea of the quest's difficulty, enhancing the decision-making process for engaging with a quest.

## Technical Perspective

From a technical standpoint, this will involve adding a dropdown menu or radio buttons to the quest posting form that allows users to choose from predefined options for complexity levels (e.g., Very Easy, Easy, Medium, Hard, Very Hard). These options will need to be stored as attributes in the Quest model within the database. Technologies likely involved are ASP.NET Core for backend logic and Angular for frontend implementation.

## User Perspective

From a user's viewpoint, this feature offers a way to better articulate the challenge posed by their quest. Quest solvers can quickly gauge whether a quest is suitable for their skills and decide if they want to engage.

## Acceptance Criteria

1. The quest posting form should include a dropdown menu or radio buttons for setting the quest's complexity level.
2. The selected complexity level should be stored in the database along with other quest details.
3. The complexity level should be displayed alongside each quest in lists or search results.
4. The implementation must not introduce any security vulnerabilities.

## What Students Will Learn

1. How to extend a form to include additional attributes.
2. How to modify the database schema to accommodate new features.
3. How to use Angular for front-end updates.
4. User Experience considerations for intuitive design.

## Hints and Suggestions

**Internet Search Suggestions:**

- ASP.NET Core form extension
- Angular dropdown menus
- Data validation in ASP.NET Core

**ChatGPT Prompts:**

- "How to implement a dropdown menu in Angular?"
- "What are the best practices for adding a new field to a database in ASP.NET Core?"
