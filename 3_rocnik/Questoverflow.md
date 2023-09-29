# AppsLab Curriculum 2023-2024 ASP.NET Core with Angular

## Project Name: QuestOverflow

QuestOverflow is an engaging and interactive web application that gamifies the learning process through quests and solutions. It is based on the model of popular Q&A platforms such as StackOverflow, but instead of traditional question and answer sessions, it introduces a unique, fun, and educational experience in the form of quests and solutions. This application is developed using the ASP.NET Core framework for backend development, EF Core for database management, and Angular for frontend development.

The primary features of QuestOverflow are:

1. **User Registration and Profile Management:**
New users can register to the application providing necessary information. Once registered, they can set up their profiles, showcasing their level, total reward points, the guild they belong to, and their accomplished quests.

2. **Quest Posting and Solving:**
Users can post "quests," or complex problems requiring creative solutions. Any user can attempt to solve these quests. When a quest is solved, the user who posted the quest can mark it as solved, and the solver is rewarded with points.

3. **Reward Points and Leveling:**
Users earn reward points when they solve quests. As users accumulate more points, they can level up. Each level up increases the complexity of quests they can solve or post, thus enriching their problem-solving skills and enhancing their learning experience.

4. **Guild Creation and Joining:**
Users have the ability to create and manage "guilds" - groups of users working together to tackle more challenging quests. Each guild generates a unique hash code, and users can join a guild using this code. However, a user can be a part of only one guild at any given time.

5. **Dashboard:**
Every user has a personal dashboard where they can track their progress, view their solved and posted quests, monitor their guild activities, and check their reward points and level status.

6. **Guild Boards:**
Each guild has a board where members can communicate, collaborate on quests, and share solutions. It encourages teamwork and helps guild members to learn from each other.

7. **Quest Search and Filter:**
A powerful search functionality enables users to find quests based on keywords, difficulty levels, or within their guilds. Users can also filter quests based on their status - open or solved.

8. **Data Security and Integrity:**
The use of ASP.NET Core and EF Core ensures high data security and integrity. User data is securely stored and managed, ensuring user privacy and data protection.

QuestOverflow thus offers an engaging platform for learners to expand their knowledge while enjoying the process. It combines gamification with education, facilitating productive collaboration, and competitive learning.

## Features

As a Product Owner, the following features are key to our application, QuestOverflow:

0. **Development Environment Setup:** This is a prerequisite for all follow up features - preparing the development environment.

1. **Utilize Provided Registration and Login Capabilities:** This feature will use existing VS2022 template for creating ASP.NET Core with Angular web application including .NET 7 and Individual Account Authentication.

2. **Profile Management:** Users can manage their profiles, which include their personal information, (display picture), level, guild affiliation, and history of posted and solved quests.

3. **Quest Posting:** This feature allows users to post new quests. They can specify the quest details, complexity level, and the expected solution approach.

4. **Quest Solving:** Users can view and solve quests posted by other users. They can submit their solutions for the quest poster's review.

5. **Reward Points Allocation:** A system that automatically allocates reward points to users based on their quest-solving activity. The complexity of the solved quest would affect the amount of reward points earned.

6. **Leveling System:** A leveling system that promotes users to higher levels based on their accumulated reward points. Higher levels unlock more complex quests.

7. **Guild Creation and Member Limit:** Users can create new guilds, each generating a unique hash code which can be used by others to join. To maintain fair competition and encourage strategic collaboration, each guild is capped at a maximum of 7 members. Once this cap is reached, the guild will no longer accept new members until a spot becomes available.

8. **Guild Joining:** A feature that allows users to join an existing guild using its unique hash code. Note, users can only belong to one guild at a time.

9. **Dashboard:** A personalized user dashboard to display progress, active quests, completed quests, guild activities, reward points, and current level.

10. **Guild Leaderboard and Competition:** A dynamic leaderboard feature that ranks guilds based on their total accumulated reward points. This feature fosters a healthy competition among the guilds, motivating users to solve more quests and earn more points for their guild. The leaderboard will be updated in real-time, displaying the top performing guilds in the platform. It's important to note that the maximum member count for each guild is capped at 7 to ensure fair competition. This limitation also encourages more strategic quest selection and cooperative problem-solving within each guild.

11. **Quest Search and Filter:** A robust search and filter functionality to easily find quests based on various parameters such as keywords, complexity level, and guild.

12. **Mobile Responsiveness:** The application should be mobile responsive to ensure seamless user experience on all devices.

## User Stories

### Feature: Development Environment Setup

- As a developer, I want to have Visual Studio 2022 installed and configured, so that I have a platform for developing the web application.
- As a developer, I want to use the existing "ASP.NET Core with Angular" template in Visual Studio 2022, so that I can start the development with a preset structure and save setup time.
- As a developer, I want to add Angular Material to the Angular project, so that I can leverage its comprehensive suite of pre-built components, themes, and tools to enhance the UI development.
- As a developer, I want to install and configure Entity Framework Core (EF Core) for ASP.NET Core, so that I can start setting up the database models and handle the database operations.
- As a developer, I want to ensure that all the necessary Npm or NuGet packages are installed and up to date, so that I can use the latest features and improvements for the development.

### Feature: Utilize Provided Registration and Login Capabilities

- As a developer, I want to use the pre-built registration page provided by the "ASP.NET Core with Angular" template, so that new users can understand what information is required to create a new account without me having to build it from scratch.
- As a developer, I want to use the built-in feature that allows users to sign up using their email address, so that they can set up a new account with their personal email and I can avoid implementing it manually.
- As a developer, I want to rely on the secure method provided by the template for users to create a password for their account, so that their account security is ensured.
- As a developer, I want to use the pre-built intuitive login page, so that registered users can quickly log in to their account without additional design and development.
- As a developer, I want to use the existing feature that allows users to log in using their email and password, so that they can access their account without needing to implement it myself.
- As a developer, I want to use the logout feature provided by the template, so that users can ensure their account is secure when they finish their session without needing extra coding.

### Feature: Profile Management

- As a registered user, I want to be able to navigate to my profile page, so that I can view and manage my profile information.
- As a registered user, I want to be able to edit my personal information such as name, email, etc., so that my profile reflects my up-to-date information.


### Feature: Dashboard

- As a user, I want to log in to the system so that I can access my personalized dashboard on my home page.
- As a user, I want to see my total accumulated reward points prominently displayed on my dashboard so that I can keep track of my progress.
- As a user, I want to see my current level on the dashboard so that I know my standing in the gamified system.
- As a user, I want to see a list of my active quests on the dashboard so that I can easily access and manage them.
- As a user, I want to see a list of my completed quests on the dashboard so that I can track my achievements.
- As a user, I want to be able to directly access a quest from my quest history in my profile, so that I can review or revisit it.
- As a user, I want to see the recent activities of my guild on the dashboard so that I can stay updated with my guild’s progress.
- As a user, I want to see my guild's name and the guild members on my dashboard so that I can quickly access my guild's details.
- As a user, I want to see which guild I am part of on my profile, so that others know which group I'm associated with.
- As a user, I want the option to leave my current guild through my profile, so that I can join a new one if I wish.

### Feature: Quest Posting

- As a user, I want a "Create Quest" button on my home page, so that I can initiate the quest creation process.
- As a user, I want to see a quest creation form when I click on the "Create Quest" button, so that I can input the details of the new quest.
- As a user, I want to be able to enter the title of my quest in the creation form, so that I can provide a brief explanation of what the quest is about.
- As a user, I want to enter a detailed description of my quest, so that other users will understand what the quest is about and what is expected from them.
- As a user, I want to select a complexity level for my quest from predefined options (e.g., Very Easy, Easy, Medium, Hard, Very Hard), so that potential solvers can gauge the difficulty of my quest.
- As a user, I want to click a "Post Quest" button to finalize and publish my quest, so that it becomes visible to other users.
- As a user, after posting the quest, I want to see a confirmation message and my quest appearing on the quest list page, so that I know the quest posting process was successful.

### Feature: Quest Solving

- As a user, I want to browse the list of available quests so that I can choose one to solve.
- As a user, I want to search quests based on keywords so that I can quickly find quests that interest me.
- As a user, I want to select a quest so that I can view its details and attempt to solve it.
- As a user, I want to solve a quest by submitting my solution so that I can earn reward points.
- As a user, I want to track the status of my submitted solution so that I know when it has been reviewed.
- As a user, I want to receive feedback on my solution so that I can improve my problem-solving skills.

### Feature: Reward Points Allocation

- As a quest creator, I want to assign a complexity level to the quests I post so that solvers know the difficulty and potential reward points of the quest.
- As a quest solver, I want to be able to submit my solution to a quest so that I can earn reward points based on the quest's complexity.
- As a quest creator, I want to be able to review and verify the solutions submitted by users so that appropriate reward points can be allocated.
- As a system, I want to automatically allocate reward points to the user who solved the quest based on its complexity level after the solution is verified and marked as correct.
- As a user, I want my reward points to be accumulated in my account after each successful quest solution so that I can track my total earned points.
- As a user, I want to see the reward points I earned from each solved quest and the total points on my dashboard so that I can keep track of my achievements.

### Feature: Leveling System (BONUS)

- As a registered user, I want to see my current level and accumulated reward points so that I can understand my current position.
- As a registered user, I want to earn reward points when I solve quests so that I can increase my accumulated reward points and level up.
- As a registered user, I want to see how many more reward points I need to accumulate to reach the next level so that I can set goals for myself.
- As a registered user, I want to check my level compared to other users so that I can see my standing in the QuestOverflow community.

### Feature: Guild Creation and Member Limit (BONUS)

- As a user, I want to access the "Create Guild" page from the main menu so that I can start the process of creating a new guild.
- As a user, I want to enter the guild's name, a brief description, and specify its focus area, so that other users can understand what the guild is all about.
- As a user, once I confirm the guild creation, I want the system to create the guild and generate a unique hash code, and I should be informed about the guild's member limit of 7, so that other users can join using this code.
- As a user, after creating a guild, I want to view its details including the unique hash code, member count, and the member limit, so that I can verify its creation and share the hash code with other users.
- As a guild creator, I want to be able to edit the guild's details, in case there's a need to update the description or focus area.
- As a guild creator, I want to be able to disband the guild, in case it's no longer needed or active. When the guild is disbanded, all members should be informed about it.
- As a user attempting to join a guild, if the guild has reached its member limit, I want to receive a message indicating that the guild is currently full, so that I can try to join another guild or wait for a spot to open up in this guild.

### Feature: Guild Joining (BONUS)

- As a user, I want to see an option on the platform that allows me to join a guild, so that I know where to start the joining process.
- As a user, I want to be able to enter the unique hash code of a guild I wish to join, so that I can request to join a specific guild.
- As a user, I want the system to check if I am already a member of any guild before I can join a new one, so that I ensure I am not violating the "one-guild-at-a-time" rule.
- As a user, after I enter the guild hash code and am not a member of any other guild, I want to receive a confirmation of my request, so that I am aware that my joining process is successful.
- As a user, after I successfully join a new guild, I want to be redirected to my new guild's board, so that I can start participating in the guild activities immediately.

### Guild Leaderboard and Competition (BONUS)

- As a new guild member, I want to be able to contribute reward points to my guild so that our guild can climb the leaderboard.
- As a guild member, I want to view the total reward points of my guild, so that I can keep track of our progress and contribution towards the leaderboard.
- As a guild member, I want to see the limit of guild members (i.e., 7), so that I understand the constraints we're working with for the competition.
- As a guild member, I want to be able to view the leaderboard of all guilds, so that I can know our guild's position in the competition.
- As a user without a guild, I want to be able to view the leaderboard, so that I can make an informed decision about which guild to join.

### Quest Search and Filter (BONUS)

- As a user, I want to be able to search for quests using keywords so that I can find quests that match my interests.
- As a user, when I search for quests using keywords, I want to view a list of matching quests so that I can choose which one to explore further.
- As a user, I want to easily clear my search input and filters so that I can start a new search.

### Mobile Responsiveness (BONUS)

- As a user, I want the application to automatically adjust its layout based on my device's screen size so that I can easily view and navigate the application on different devices, including smartphones, tablets, and desktops.
- As a user, I want the navigation menu to be responsive so that it adjusts appropriately for mobile viewing, perhaps transitioning to a hamburger menu or similar, allowing me to easily navigate the site on my mobile device.
- As a user, I want the application's buttons, forms, and other interactive elements to be touch-friendly so that I can easily interact with them on my touch screen devices.

## Sprints

### Sprint 1: Development Environment Setup & Utilize Provided Registration and Login Capabilities

- Feature: Development Environment Setup
  - [As a developer, I want to have Visual Studio 2022 installed and configured, so that I have a platform for developing the web application.](1_polrok/user_stories/Setting%20Up%20Visual%20Studio%202022%20for%20Development.md)
  - [As a developer, I want to use the existing "ASP.NET Core with Angular" template in Visual Studio 2022, so that I can start the development with a preset structure and save setup time.](1_polrok/user_stories/Utilizing%20ASP.NET%20Core%20with%20Angular%20Template%20in%20Visual%20Studio%202022.md)
  - [As a developer, I want to install and configure Entity Framework Core (EF Core) for ASP.NET Core, so that I can start setting up the database models and handle the database operations.](1_polrok/user_stories/Install%20and%20Configure%20Entity%20Framework%20Core%20(EF%20Core)%20for%20ASP.NET%20Core.md)
  - [As a developer, I want to ensure that all the necessary Npm or NuGet packages are installed and up to date, so that I can use the latest features and improvements for the development.](1_polrok/user_stories/Ensuring%20Necessary%20Package%20Installation%20and%20Updates.md)

- Feature: Utilize Provided Registration and Login Capabilities
  - [As a developer, I want to use the pre-built registration page provided by the "ASP.NET Core with Angular" template, so that new users can understand what information is required to create a new account without me having to build it from scratch.](1_polrok/user_stories/Utilize%20Pre-Built%20Registration%20Page%20in%20ASP.NET%20Core%20with%20Angular.md)
  - [As a developer, I want to use the built-in feature that allows users to sign up using their email address, so that they can set up a new account with their personal email and I can avoid implementing it manually.](1_polrok/user_stories/Implementing%20Built-in%20Email%20Signup.md)

### Sprint 3: Profile Management

- Feature: Profile Management
  - [As a registered user, I want to be able to navigate to my profile page, so that I can view and manage my profile information.](1_polrok/user_stories/Navigate%20to%20Profile%20Page%20for%20Managing%20User%20Information.md)
  - [As a registered user, I want to be able to edit my personal information such as name, email, etc., so that my profile reflects my up-to-date information.](1_polrok/user_stories/Edit%20Personal%20Information%20in%20User%20Profile.md)
  - [As a registered user, I want to see my current level displayed on my dashboard, so that I am aware of my progress.](1_polrok/user_stories/Display%20Current%20Level%20on%20User%20Dashboard.md)
  - [As a registered user, I want to see which guild I am part of on my dashboard, so that others know which group I'm associated with.](1_polrok/user_stories/Display%20Guild%20Affiliation%20on%20User%20Dashboard.md)

### Sprint 4: Profile Management (Part 2)

- Feature: Profile Management
  - [As a registered user, I want the option to leave my current guild through my profile, so that I can join a new one if I wish.](1_polrok/user_stories/Guild%20Departure%20Option%20in%20User%20Profile.md)
  - [As a registered user, I want to view a list of all quests I have posted or solved, so that I can keep track of my contributions and solutions.](1_polrok/user_stories/View%20Posted%20and%20Solved%20Quests.md)
  - [As a registered user, I want to be able to directly access a quest from my quest history in my profile, so that I can review or revisit it.](1_polrok/user_stories/Direct%20Access%20to%20Quests%20from%20Profile%20History.md)
  - [As a registered user, I want to see my total accumulated reward points on my profile, so that I know how close I am to leveling up.](1_polrok/user_stories/Display%20Total%20Accumulated%20Reward%20Points%20on%20User%20Profile.md)

### Sprint 5: Quest Posting

- Feature: Quest Posting
  - [As a user, I want a "Create Quest" button on my home page, so that I can initiate the quest creation process.](1_polrok/user_stories/Add%20Create%20Quest%20Button%20to%20Home%20Page.md)
  - [As a user, I want to see a quest creation form when I click on the "Create Quest" button, so that I can input the details of the new quest.](1_polrok/user_stories/Quest%20Creation%20Form%20Implementation.md)
  - [As a user, I want to be able to enter the title of my quest in the creation form, so that I can provide a brief explanation of what the quest is about.](1_polrok/user_stories/Quest%20Title%20Entry%20in%20Creation%20Form.md)
  - [As a user, I want to enter a detailed description of my quest, so that other users will understand what the quest is about and what is expected from them.](1_polrok/user_stories/Enter%20Detailed%20Description%20for%20Quests.md)
  - [As a user, I want to select a complexity level for my quest from predefined options (e.g., Very Easy, Easy, Medium, Hard, Very Hard), so that potential solvers can gauge the difficulty of my quest.](1_polrok/user_stories/Quest%20Complexity%20Level%20Selection.md)
  - [As a user, I want to click a "Post Quest" button to finalize and publish my quest, so that it becomes visible to other users.](1_polrok/user_stories/Posting%20a%20New%20Quest.md)
  - [As a user, after posting the quest, I want to see a confirmation message and my quest appearing on the quest list page, so that I know the quest posting process was successful.](1_polrok/user_stories/Quest%20Posting%20Confirmation%20and%20Listing.md)

### Sprint 6: Quest Solving

- Feature: Quest Solving
  - As a user, I want to browse the list of available quests so that I can choose one to solve.
  - As a user, I want to search quests based on keywords so that I can quickly find quests that interest me.
  - As a user, I want to select a quest so that I can view its details and attempt to solve it.
  - As a user, I want to solve a quest by submitting my solution so that I can earn reward points.
  - As a user, I want to track the status of my submitted solution so that I know when it has been reviewed.
  - As a user, I want to receive feedback on my solution so that I can improve my problem-solving skills.

### Sprint 7: Reward Points Allocation

- Feature: Reward Points Allocation
  - As a quest creator, I want to assign a complexity level to the quests I post so that solvers know the difficulty and potential reward points of the quest.
  - As a quest solver, I want to be able to submit my solution to a quest so that I can earn reward points based on the quest's complexity.
  - As a quest creator, I want to be able to review and verify the solutions submitted by users so that appropriate reward points can be allocated.
  - As a system, I want to automatically allocate reward points to the user who solved the quest based on its complexity level after the solution

### Sprint 8

- **Feature: Leveling System (BONUS)**
  - As a registered user, I want to see my current level and accumulated reward points so that I can understand my current position.
  - As a registered user, I want to earn reward points when I solve quests so that I can increase my accumulated reward points and level up.
  - As a registered user, I want to see how many more reward points I need to accumulate to reach the next level so that I can set goals for myself.
  - As a registered user, I want to check my level compared to other users so that I can see my standing in the QuestOverflow community.

### Sprint 9

- **Feature: Guild Creation and Member Limit (BONUS)**
  - As a user, I want to access the "Create Guild" page from the main menu so that I can start the process of creating a new guild.
  - As a user, I want to enter the guild's name, a brief description, and specify its focus area, so that other users can understand what the guild is all about.
  - As a user, once I confirm the guild creation, I want the system to create the guild and generate a unique hash code, and I should be informed about the guild's member limit of 7, so that other users can join using this code.
  - As a user, after creating a guild, I want to view its details including the unique hash code, member count, and the member limit, so that I can verify its creation and share the hash code with other users.
  - As a guild creator, I want to be able to edit the guild's details, in case there's a need to update the description or focus area.
  - As a guild creator, I want to be able to disband the guild, in case it's no longer needed or active. When the guild is disbanded, all members should be informed about it.

### Sprint 10

- **Feature: Guild Joining (BONUS)**
  - As a user, I want to see an option on the platform that allows me to join a guild, so that I know where to start the joining process.
  - As a user, I want to be able to enter the unique hash code of a guild I wish to join, so that I can request to join a specific guild.
  - As a user, I want the system to check if I am already a member of any guild before I can join a new one, so that I ensure I am not violating the "one-guild-at-a-time" rule.
  - As a user, after I enter the guild hash code and am not a member of any other guild, I want to receive a confirmation of my request, so that I am aware that my joining process is successful.
  - As a user, after I successfully join a new guild, I want to be redirected to my new guild's board, so that I can start participating in the guild activities immediately.

### Sprint 11

- **Feature: Dashboard (BONUS)**
  - As a user, I want to log in to the system so that I can access my personalized dashboard on my home page.
  - As a user, I want to see my total accumulated reward points prominently displayed on my dashboard so that I can keep track of my progress.
  - As a user, I want to see my current level on the dashboard so that I know my standing in the gamified system.
  - As a user, I want to see a list of my active quests on the dashboard so that I can easily access and manage them.
  - As a user, I want to see a list of my completed quests on the dashboard so that I can track my achievements.
  - As a user, I want to see the recent activities of my guild on the dashboard so that I can stay updated with my guild’s progress.
  - As a user, I want to see my guild's name and the guild members on my dashboard so that I can quickly access my guild's details.

### Sprint 12

- **Feature: Guild Leaderboard and Competition (BONUS)**
  - As a new guild member, I want to be able to contribute reward points to my guild so that our guild can climb the leaderboard.
  - As a guild member, I want to view the total reward points of my guild, so that I can keep track of our progress and contribution towards the leaderboard.
  - As a guild member, I want to see the limit of guild members (i.e., 7), so that I understand the constraints we're working with for the competition.
  - As a guild member, I want to be able to view the leaderboard of all guilds, so that I can know our guild's position in the competition.
  - As a user without a guild, I want to be able to view the leaderboard, so that I can make an informed decision about which guild to join.

### Sprint 13

- **Feature: Quest Search and Filter (BONUS)**
  - As a user, I want to be able to search for quests using keywords so that I can find quests that match my interests.
  - As a user, when I search for quests using keywords, I want to view a list of matching quests so that I can choose which one to explore further.
  - As a user, I want to easily clear my search input and filters so that I can start a new search.

### Sprint 14

- **Feature: Mobile Responsiveness (BONUS)**
  - As a user, I want the application to automatically adjust its layout based on my device's screen size so that I can easily view and navigate the application on different devices, including smartphones, tablets, and desktops.
  - As a user, I want the navigation menu to be responsive so that it adjusts appropriately for mobile viewing, perhaps transitioning to a hamburger menu or similar, allowing me to easily navigate the site on my mobile device.
  
### Sprint 15

- **Feature: Mobile Responsiveness (BONUS) continued**
  - As a user, I want the application's buttons, forms, and other interactive elements to be touch-friendly so that I can easily interact with them on my touch screen devices.
