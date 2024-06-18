# CodePath-Week-2-Capstone-submit
the repo I'm making to fulfill the codepath week 2 submission



Meta University Eng Project Plan Template     
Fill in blanks (enclosed by brackets []) and remove red text as you work through writing your project plan. Your project plan should be a living document and can be changed as you progress through the internship. Make sure to work on this document together with your manager to get feedback, as well as ensuring your project meets the requirements and expectations in the Project Guide.
EconMetrics
Intern: Carson Wolber
Intern Manager: William La
Intern Director: Vicky Wang
Peer(s): James Pang, Minh Lam
GitHub Repository Link: https://github.com/CWMetaUCapstone/EconMetrics

Overview
EconMetrics is a platform for users to analyze and receive insights into their personal finances. Users can also view the anonymized budgets and spending habits of other users to promote transparency and a direct source of inspiration for improving one’s spending habits. 

Category: Finance
Story: A platform for users to view other’s anonymized budgets and upload their own budgets to symbiotically benefit by contributing to a crowdsourced budget database and in turn receive an array of analytics and statistics to help users improve their personal finances
Market: The service is useful for anyone wanting to track and improve their personal finances, however from a “data company” POV, the service would be useful to data scientists, economists, social scientists, etc. who could use data gathered for research insights. 
Habit: User data will likely sync with their transaction history on a weekly basis, correspondingly, users in ordinary circumstances will likely visit the site weekly once new data syncs. Other use cases are at inflection points such as moving, new job, any event that will severely impact someone’s finances and they want guidance/insight into how their new standard of living
Scope: Initially, the service will allow users to view anonymized user profiles to see and compare budgets across users with a basic breakdown into percentages across a few fundamental categories (e.g. housing, food, transportation, etc.). 

Product Spec

User Stories
User stories are actions that the user should be able to perform in your app.

First, focus and identify functionality that is required for your MVP (Minimum Viable Product) that conforms to all the project requirements and expectations. Make sure your technical challenges are part of your MVP.

You should also identify optional / nice-to-have functionalities that would be done as stretch goals during MU Week 8 and 9. Remember, technical challenges should not be optional features, they must be code complete before the end of Week 8!
Required
User can login
User can create an account
User can link bank account via Plaid for transactions API
Users can view a basic breakdown of their spending habits across a set of categories
User can see their profile
User can fill out relevant profile info (salary, address, career, company)
Users can search for other profiles through an array of filters/sorts on various metrics

Optional
Users can interact with a map/filter to view the profiles of users within a user-determined radius of themselves
Users can receive automatic analytics on how their category breakdown compares to other users with similar profiles (e.g. of users in the same city & salary range as you, you spend 17% more on rent than average) 
User can edit their profile information
Developers and Researchers can utilize an API service to interact with anonymized user data
Users can join forums for different groups (i.e. across salary, city, company) to discuss personal finance.  
User passwords are encrypted in the database for security
Users can set and track basic goals (e.g. get my monthly spending on rent down to 20%) 
Some basic gamification (e.g. a leaderboard for percent of income invested for each salary-range) 
A resources page that gives users links to various relevant financial planning resources
Screen Archetypes



Data Model
[Describe the data you’re going to need to back your application. This can include database models (like tables), or external data you’ll require from some API.]

Plaid Transactions API will provide user transactions in a JSON format to parse and analyze. Internally, user profiles are stored in a table. [CONTINUE HERE]

Server Endpoints
[Describe the endpoints that your application is going to consume from your server. If you’re using REST, then you’ll probably want to include the method (GET/POST/etc) and the expected parameters (query parameters, body parameters, etc.)]
Navigation

Project Requirements
[Based on the Project Guide, describe how your project is going to be fulfilling each of the base project requirements.]

Technical Challenges
For your project, you should demonstrate that you can apply what you’ve learned so far and expand on that knowledge to write code and implement features that go beyond the scope of the projects you worked on during CodePath.

Based on the general idea and direction of your project requirements, your intern manager will create at least two (2) Technical Challenges for you. This section is all about explaining what they are and how you’re planning to tackle them - you’ll work together with your manager to fill it out. 

Technical Challenge #1 - [Name/Small Description]
What
What problem are you solving, and what parts go beyond what you learned in CodePath? 
How
Explain in words how you’ll solve this problem. 

You’re encouraged to expand on this section with pseudo-code, links to external frameworks, architecture / design diagrams, anything that you can use to explain this to others!
Technical Challenge #2
What
How

Database Integration
[Describe what you are using for database storage. For example, Parse, MongoDB, Sequelize, etc.]

External APIs
[Describe at least one external API you’re using for your project. For example, Google Maps, Spoonacular, OpenWeather, etc.]

Authentication
[Describe how user authentication is handled for your project, including logging in and signing up. Also describe any kind of cookie / session management you’re doing and how you’re implementing it, and how this affects navigation between different screens by the same user.]

Visuals and Interactions
[Provide details on how your app is fulfilling the following UI craft requirements, and how these are technically accomplished.]

Interesting Cursor Interaction
UI Component with Custom Visual Styling
Loading State

Timeline
Project execution will start in Week 4 of MU. Based on the previously defined requirements, user stories and technical challenges, use the following table to scope out and plan a timeline for deliverables over Week 4 - 9. You can be as detailed as you need, ranging from simply mentioning the user stories, or dividing them into sub-tasks.

You are free to modify the table, add / remove rows or columns, whatever fits your style! The important thing here is that you focus and prioritize certain aspects of your project so you don’t get behind and are ready to deliver the MVP - remember your required features should be code complete before the end of Week 8, including both technical challenges!

We also encourage you to leverage project tracking tools such as GitHub Issues or Meta’s internal Tasks / GSD tooling to keep manage individual units of work.

MU Week
Project Week
Focus
User Stories
4
1
Focus on the components that will serve as the skeleton of your project. You will probably be using most of what you learned in CodePath to set up things like the client and server repositories, initial routing, login / registration, creating a database with object models, etc.
Example:
User can login
User can create an account
[Optional] User passwords are encrypted in the database for security
5
2
Week 5 and 6 should be where you focus on the specific requirements of your project.
Example:
User can create / edit / delete posts
User can chat with other users in real-time (e.g. technical challenge)
6
3
By this point, you should be getting started with your technical challenges as well.


7
4
You should focus on finishing your MVP and core requirements. By this point, you should be done with at least one of your technical challenges.


8
5
Continue work on finishing touches and stretch goals for your MVP. By this point, your core functionality and both TAPs should all be in place. It is also a good point to start working on stretch goals that could further expand on the functionality (and technical complexity) of your project.

This week you also have to submit your self-review, make sure you allocate enough time for this alongside your final submission for your project!


9
6
It’s time to show others what you have built! Work on a presentation and demo that you will present to other interns to showcase your work. You are also free to continue polishing and expanding on your project!


10
7
For this week, we have a bunch of extra activities prepared to give you a quick dive of what it is to work at Meta. You will find activities around using internal tools and frameworks, and even committing code to our internal repositories.




