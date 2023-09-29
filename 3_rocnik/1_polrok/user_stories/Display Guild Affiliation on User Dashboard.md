# User Story: Display Guild Affiliation on User Dashboard

## Description

The purpose of this user story is to enhance the user dashboard by displaying guild membership status. Registered users should be able to see which guild they are a part of, making it easy for other users to identify their group affiliations.

## Technical Perspective

From a technical standpoint, this involves updating the User model to include a field for `GuildId` or `GuildName`. You'll need to extend the User API to populate this field during user fetch operations and adapt the Angular component responsible for displaying the user profile to include this new piece of information.

The backend could be implemented using ASP.NET Core, and you may leverage Entity Framework Core for handling the database interaction. For the frontend, Angular will be employed to display the guild information seamlessly within the profile UI.

## User Perspective

End-users will find their dashboard section now displays their guild affiliation. This is crucial for guild-based operations and adds another layer of social interaction and identity to the platform. Users would expect this piece of information to be accurate and updated in real-time, reflecting any changes like joining a new guild or leaving one.

## Acceptance Criteria

1. The user profile API must return a field for `GuildId` or `GuildName`.
2. The user profile UI should display the guild name based on the `GuildId` or `GuildName` returned.
3. If a user is not a part of any guild, a message stating "No Guild Affiliation" should be displayed.
4. The displayed guild information should update in real-time if a user joins or leaves a guild.

## What Students Will Learn

1. Backend development: How to extend existing APIs using ASP.NET Core.
2. Frontend development: Learning to update Angular components based on dynamic data.
3. Database Management: Working with Entity Framework Core for updating and fetching relational data.
4. Real-time Data Management: Ensuring the UI reflects real-time changes in backend data.

## Hints and Suggestions

**Internet Search Suggestions:**

- ASP.NET Core API extension
- Angular dynamic components
- Entity Framework Core relations

**ChatGPT Prompts:**

- "How to extend an existing API using ASP.NET Core?"
- "What are the best practices for updating Angular components based on dynamic data?"

**Further Learning:**

- [Link to official ASP.NET Core documentation for extending APIs](https://dotnet.microsoft.com/en-us/apps/aspnet/apis)
- [Link to Angular documentation for dynamic component rendering](https://angular.io/guide/dynamic-component-loader)
- [Link to Entity Framework Core documentation for working with relations](https://learn.microsoft.com/en-us/ef/core/modeling/relationships)
