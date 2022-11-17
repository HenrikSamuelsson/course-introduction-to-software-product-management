# Client Needs and Software Requirements

Notes on the the course Client Needs and Software Requirements.

## Introduction to Requirements

### What is a Requirement/Requirement Activities

The following definition of a requirement is used in the course:

> Requirements are specific descriptions of your client's needs.

## User Interaction

This module is about client interactions and requirements elicitation and expression.

### Restaurant Scenario

An app for ordering food at an restaurant will be the basis for material discussed in this module. The desire of the client is that the app shall have a set of features related to ordering food, such as special view for kids, possibility to notify the kitchen about special requirements on the food, and it shall be possible to pay for the food through the app.

### User Considerations

### Involving Clients

### Use Cases

Use case explains a given feature of the product in a way that every one can comprehend regardless of background and formal training. Use cases help to organize and clarify what a product shall do.

Use cases are commonly organized in tables wih some or all of the following elements:

- Name
- Participating Actors
- Goals
- Triggers
- Pre-Condition
- Post-Condition
- Basic Flow
- Alternate Flows
- Exceptions
- Qualities

### Wireframes

### Storyboards

## Writing Requirements

### Agile Requirements

Requirements are an integral part of agile. Requirements will often change as more facets of the products are discovered during product development. Agile methodologies support changes to requirements
by integrating the customer and working iteratively with feedback built in to the process.

### User Stories

User stories express requirements in a consistent format intended to make them easy to write and understand:

> As a **who**  
> I want to **what**  
> So that **why**  

Who is a type of use, what is a goal, and why is a reason.

A concrete example of a user story from a job bank application:

> As a job seeker  
> I want to see job openings in a location zone  
> so that the commute distance is viable  

User stories can be evaluated using the mnemonic INVEST which stands for:

- Independent
- Negotiable
- Valuable
- Estimatable
- Small
- Testable

### Acceptance Tests

Acceptance tests verifies that the requirement described by a user story have been meet. There is a link between user stories and acceptance test, sometimes if having written user stories on index cards so are the acceptance test written on the back of the index card.

An acceptance test is built on a set of acceptance criteria's. Acceptance tests and acceptance criteria's shall be written in simple straightforward way without room for different interpretations.

Note that acceptance criteria an acceptance test are not the same thing.

Acceptance criteria is one condition that need to be met in order to accept the story as complete. There will usually be multiple acceptance criteria's for a given story.

Acceptance test is a scenarios which is derived from acceptance criteria.

Example of acceptance criteria's for registering at a site with different forms of credentials:

- Registration shall be able to be made with a chosen password and email address
- Registration shall be able to be made with an existing Facebook account
- Registration shall be able to be made with an existing Google account
- Already used credentials shall not be able to be used again
- Credential shall be verified for correctness

Acceptance test for trying to register with an already registered email:

 1. Chose to register with user name and email password
 2. Fill in a password in the displayed password field
 3. Fill in a already registered email address in the email field
 4. Confirm that a message is display that the email was not accepted du to being used already
 5. Confirm that there is a button for requesting a password reset email  

### Product Backlog

A product back log is a list of task of what needs to be done during a development project. The main part of the task will be related to user stories and requirements but can also be knowledge tasks to learn something, bugs to be corrected, physical tasks like setup of test systems.

The work shall be split into smaller parts by having features or different user stories. Each of these parts shall then be prioritized by the clent, the most important tasks are placed at the top of the back log and shall be done first. Task that are blocked will be push down in the backlog.

The backlog is important for planning in Scrum where for each sprint (iteration) a number of back log items are planned in to be done. After then after a number of sprints there will be a release.

The backlog will be reorganized during the product development. user stories priority will be changed as new things are discovered. New tasks will commonly be added and tasks might be removed due to not being need to be done at all.

### Story Maps

Story maps shows what to build and maintain visibility for how it all fits together. They enable user-centred conversations, collaboration, and feature prioritization to align and guide iterative product development.

A story map is a two-dimensional view with cards/cells organized rows and columns. Top rows holds an overview about what should be done an details about tasks/functionality are added in the content of the lower rows. More prioritized tasks are organized higher up than low priority tasks.

A correctly organized story map will enable for everyone in the team to understand what will be need to developed first to at least have a "walking skeleton" product ready as soon as possible.

## Quality Requirements

### Criteria for User Stories

Beyond the qualities described by the INVEST mnemonic so are there several other criteria that user stories should meet:

- Correctness: Mistakes in user stories mean developing the wrong thing and this is waste
- Completeness: Missing information will lead to a product with missing features in the implementation
- Clearness: Leave as little as possible up for interpretation and guessing
- Consistency: Not possible to know hom to develop if it says different things at different places
- Feasibility: Must realistic to acheive the development goals technically and with the available resources
- Traceability: Requirements and user stories shall be linked to the produced artifacts such as code and tests

### Ambiguous Requirements

### Course Summary
