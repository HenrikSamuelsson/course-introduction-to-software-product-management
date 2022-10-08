# Software Processes and Agile Practices

Notes on the course Software Processes and Agile Practices.

## Introduction to Processes

### Processes and Practices

Having a process to follow brings order to the software development aiding in not to miss out on necessary work to be done.

A process enables splitting the work into smaller parts that can be understood and handled by individual teams or single team members.

Some terms and definitions related to processes:

| Term         | Definition                                            |
| ---          | ---                                                   |
| lifecycle    | Life span of a product, from conception to retirement |
| activity     | A set of related tasks                                |
| task         | Small manageable work unit                            |
| dependency   | Relationship that specifies ordering of work units    |
| work product | Produced output upon completing a task                |
| resource     | Something that improves, advances, or funds a task    |
| role         | A job-related activity that a person takes on         |

A role performs a task and the result is that a work product is produced, resources are consumed while executing the task.

Some examples involving the above terms when developing a software product:

It is the role of the architect to perform the task of producing the high level design, and the work product will be a document with text and diagrams describing the design.

The design will then need to be reviewed by other roles such as developers and product owners, this review task produces as work product in the form of a review document.

The design task and the review task are part of the same activity.

There is a dependency between the design and the review since the design must be done before the review can be performed.

During the lifecycle of the product there might be need for adaptions. The design document can then be studied again to find out how it is suitable to adapt to support the new needs.

### Software Engineering Activities

IEEE 1074 is a standard providing a process for creating a software project life cycle process. This standard is however not free and costs more than the entire course to buy. Activities are presented in the course and I presume that these activities are derived from the standard.

There are generally four main software engineering activities:

- Project management
- Specification
- Design and implementation
- Verification and validation

Project management in ongoing for the entire project duration and includes tasks related to:

- Creating a process
- Setting standards
- Managing risks
- Performing estimations
- Allocating resources
- Making measurements
- Improving process

## Process Models

## Agile Practices

Practice is defined as a technique, rule, or guideline intended to make a process more effective. Software development practices that are based upon the Manifesto for Agile Software Development are called Agile practices. A set of practices that together are complete enough to support the entire development life cycle is known as a methodology. Methodologies based on Agile practices are known as Agile methodologies. Example of Agile methodologies are Extreme Programming, Scrum, and Lean.

## Other Practices

### Extreme Programming - XP

Extreme Programming (XP) is an Agile methodology that combines 12 effective development practices with the goal to acheive client satisfaction.

|12 Practices of XP | | | |
|---|---|---|---|
|The Planning Game|Simple Design|Pair Programming|40 Hour Work Week|
|Small Releases|Continuous Testing|Collective Code Ownership|On-Site Customer|
|System Metaphor|Refactoring|Continuous Integration|Coding Standards|

#### The Planning Game

Planning is done in collaboration by the client and the development team. Planning is done at the start of each iteration phase during the entire project development, but with a more extensive planning session at the start of the project.

Planning includes discussions on features, their priorities, and viable release schedule. The smaller planning sessions will be more detailed about the individual features to be developed and released in the upcoming iteration.

#### Small Releases

Small releases means more demos and this results in more feedback from the client which is desirable. Having a small planned release also makes the estimation simpler and more accurate.

#### System Metaphor

A system metaphor is used to explain a system to non technical stakeholders. The system metaphor enables everyone; clients, developers, and managers to understand and being able to discuss how the system works. The system metaphor is realized by giving each chunk of the code its own name. These names are choses so that they are understandable by all stakeholders of the project. For example if developing an app for purchasing clothes there would be chunks of code known as shopping cart, inventory, item, department list, and checkout.

#### Simple Design

XP defines simple design of the code as:

- Tests runs and passes
- No duplicate code
- States the programmers intent for the code clearly
- Contains the fewest possible classes and methods

There is in XP and acronym called YAGNI that stands for You Are Not Going to Need It and this means that code should never be added because you think yoy might need it in the future. Often this type of code will never be used and it will just be left there cluttering up the code base. Do not over-engineer the design for a future that may not come.
