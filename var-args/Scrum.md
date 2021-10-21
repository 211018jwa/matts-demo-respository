# Scrum

## Background
![scrum diagram](./scrum-diagram.png)

Scrum is an angile framework. In other words, it is a defined process
with actionable steps to be Agile. Borrowing terminology from OOP,
Agile is abstract, while Scrum is a concrete implementation of Agile.

The organization that developed the Scrum methodology created a guide
known as the Scrum Guide that contains information on Scrum, found
[here](https://scrumguides.org/scrum-guide.html)

They define Srcum as a "lightweight framework that helps people, teams, 
and organizatoins generate value through adaptive solutions for complex
problems".

To understand Scrum, it is important to understand what a **spring** is.
Additionally, there are three different high level ideas to be aware of.
These are the Scrum
- Artifacts
- Roles
- Ceremones

# Sprint
A Sprint is fundamentally the most important part of Scrum. It is where
ideas are transformed into actual value in the form of **usable increments**.

Sprint charateristics:
- Should be fixed in length ranging from 1 to 4 weeks (2 weeks is typical)
- The product backlog is the input to a Sprint
- A potentially shippable increment is the output for a Sprint

# Scrum Artifacts
Scrum artifacts are used to help manage work and progress that needs to be
made. There are three artifacts:
- Product backlog
    - An ordered list of everything that is currently part of the vision for
    the product
    - The prodcut backlog is always changing and is never completed
    - The product owner is responsible for creating items and maintaining the
    product backlog
        - Job title of the product owner: Product Manager
- Sprint backlog
    - List of everything that the Scrum team decides to achieve for a particular sprint
    - Once planned and decided upon, only the development team add more items to it
    - If the development team decides to remove an item from the Sprint backlog, they must
    negotiate this removal with the product owner
- Usable product increment
    - The actual product at the end of the Sprint
    - It must be "potentially releasable"

# User Story
User stories are the items contained in the product backlog and sprint backlog. They are the features to be
developed, written from the perspective of a user of the software. 

Benefits of user stories:
- Keeps the focus on the user
- Stories enable collaboration
- Stories drive creative solutions
- Stories create momentum

Reference: [Atlassian](https://www.atlassian.com/agile/project-management/user-stories)

User story format:
- You should start with
    - "As a"
    - "I want to"
    - "So that I"

    There are a couple of considerations when writing user stores:
    - Acceptance criteria
    - Definition of Done
    - Story pointing
    - Burndown charts (track progress quantitatively)

    ## Acceptance Criteria
    Acceptance criteria help to define when the functionality of a user story has actually ben implemented. From
    the perspective of a user, the criteria is what they woulld preceive as "acceptable".

    Acceptance criteria typically follows the pattern of Given/When/Then

    Example: Adding numbers(Calculator App)
    - As a user
    - I want to be able to input two numbers and click the add button
    - So that I can find the sum of those two numbers

    Acceptance criteria 1:
    - Given that I am at the add numbers ageo of the website
    - When I type in 10
    - And I type in 25
    - Add click add
    - Then I should see the result of 35

    Acceptance criteria 2:
    - Given that I am at the add numbers page of the website
    - When I do not type anything in the first input for a number
    - But I do type in 20 for the second input for a number
    - And I click add
    - Then I should receive a message that says "No number found for the first input"

     Acceptance criteria 3:
    - Given that I am at the add numbers page of the website
    - When I do type in 20
    - But I do not type anything for the second input
    - And I click add
    - Then I should receive a message that says "No number found for the second input"

     Acceptance criteria 4:
    - Given that I am at the add numbers page of the website
    - When I do not type anything in the first input
    - And I do not type in anything in for the second input
    - And I click add
    - Then I should receive a message that says "No number found for both the first and the second input"

    ## Definition of Done
    The definition of done is defined by the Scrum team. It specifies that needs to be fulfilled for a user story
    to be comsidered complete

    For example:
    - Acceptance criteria met?
    - Is the code peer reviewed?
    - Do our unit tests for the code pass?
    - Do our integration tests for the code pass?
    - Do our automated E2E tests pass?
    - Does the product owner approve of the feature that has been implemented?

    - Internal products (tools your company is going to be using)
    - Business to consumer (market research)
    - Business to business (user stories are based on what the customer wants)

    ## Story Pointing
    Story pointing is all about estimating the amount of effort to complete particular
    user story. This is accpomplished by asignning a value to a user story. Rather than
    producing a concrete estimate (days, weeks), we could use sotry points instead.

    Story points could be 
    -Fibonacci numbers (1, 1, 2, 3, 5, 8, 13, 21, 34, 55, ...)
    - T-Shirt sizes (XS, S, M, L, XL)
    - etc.

    ## Burndown chart
    ![burndown chart](./burndown-chart.PNG)

    - Used to track progress of a sprint
    - All of the user stories' story points are added up in the Spring backlog
    - As user stories are completed, the number of story points remining can be visualized
    - Should ideally go to 0 by the end of the Sprint

    # Scrum Roles
    1. Scrum Master
        - Responsible for facilitating proper Scrum practices within both the Scrum team and wide organizatoin
        - Help to clarify questions team members may hae about Scrum
        - Assist in the removal of **impediments/blockers** in whatever they can
        - Facilitate the **Scrum ceremonies**
    2. Product Owner
        - Creates and orders the product backlog items
        - Explicitly communicates product backlog items
        - Serves as the point of contact between the client and the Scrum team
    3. Development Team
        - Software engineers + testers
        - Responsible for developing usable increments in each Sprint
        - Creating a plan for the Sprint
        - Adapting their plan toward the Sprint goal
        - Holding each other accountable

    # Scrum Team
    The Scrum roles describe the roles of different people involed in a small team known as a **Scrum team**.

    A Scrum team consists of 
    - One Scrum master
    - One product owner
    - Many developers/testers

    Scrum teams shoudl ideally
    - Have 10 or fewer people
    - Have no hierarchies
    - Be cross-functional
    - Be self-managing

    # Scrum Ceremonies
    The Scrum ceremonies are the "official" Scrum meetings. Ceremonies are designed to enable the transparency required
    for adapting and improving.

    These ceremonies are of course not the only meetings not defined within the Scrum framework. It is important to make
    the most of the Scrum ceremonies/meetings in order to create shared understanding and reduce ambiguity.

    The ceremonies corresponding to a particular Sprint are as follows:
    1. Sprint planning meeting
        - Lays out work for the Sprint
        - The entire Scrum team works together
            - The product owner facilitates discussion about the most important product backlog items and how they relate to
            the product goal
            - The developers plan work that is necessary to accomplish each user story
        - No more than 8 hours


