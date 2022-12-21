# Agile Planning for Software Products

Notes on the the course Agile Planning for Software Products. This is the fourth course in the Software Product Management Specialization.

This course covers the techniques required to break down and map requirements into plans to drive software production.

Upon successful completion of this course, you will be able to:

- Create effective plans for software development
- Map user requirements to developer tasks
- Assess and plan for project risks
- Apply velocity-driven planning techniques
- Generate work estimates for software products

## Module 1 Introduction to Planning

Module 1 covers:

- Major uncertainties that projects need to resolve
- How to break down work into manageable pieces
- The difference between:
  - estimate
  - target
  - commitment

### Introduction to Planning

Recall of some terms introduced in other courses in this specialization:

| Term | Definition |
| --- | --- |
| milestone | Checkpoint to be passed in a project, measures progress |
| role | Function that a person involved in a project takes on |
| schedule | A timeline holding tasks for a  project |
| task | Small, manageable work item part of a  project |
| work product | Intermediate product produced by a task in a project|

### Uncertainty Space

There are basically two types of uncertainties in a project:

- What is to be created, also known as the ends
- How will it be created, also known as the means

There will a high degree of uncertainty at the beginning of the project and the uncertainty will shrink as the project is completed.

The two types of uncertainty can be graphed in a two dimensional chart with "what" in the vertical  direction and "how" in the horizontal direction. These types of graphs are called the uncertainty space.

The uncertainty space graphs will look different depending on how the project is executed. In water fall so will the "what" part increase early because there is a lot of up front planning. On the other side if having an ad-hoc approach so will the "how" part be dominant at the start of the project since in this type of project you will just start implementing without much planning.

### Work Breakdown Structure

A work break down structure is a hierarchical structure in which a project as a whole is split into smaller manageable parts. The hierarchy of the work break down structure can be viewed visually be creating a tree view of the project. For example by the large parts on the top and then letting each part branch out to show more details in the bottom.

Benefits of doing a work break down structure is:

- Simplifies estimates becaus a small step is easier to estimates
- Enables parallel development work because of the split of the project into chunks
- Enables tracking of progress and resource planning

## Module 2 Project Planning

Module 2 covers:

- Story point
- Task sizing
- Velocity
  - How to calculate a velocity estimate
  - Factors influencing velocity
  - What makes velocity stable
- Concept of done
  - How a story is only counted towards velocity if it is done
- Time boxing
  - Time boxing relation to Scrum
- Release
- Gantt Chart
- Release plan.

### Story Points

A story point is a unit of measurement for estimating the effort needed to complete a task. A simple task will typically be assigned one story point and more complex tasks will be assigned more points.

Story points are purposely a vague measurement of time. This relates well with that estimations of how long a SW task will take is only a educated guess. Estimating tasks in story points instead of time takes away a bit of pressure on the developers because when estimating in time this can be taken as a commitment by the managers. Story points makes it more clear that there is in reality no way to be exactly sure when things are done but there is at least a rough idea that can be used for planning future work.

### Velocity Estimates

Velocity is a number of story points completed per sprint. Measuring velocity enables estimation for how much work that can be included in the next sprint and when the project as a whole will be completed.

Measuring velocity is done in the following way:

1. Assign story points to tasks
2. Put a number of tasks into the sprint during sprint planning
3. Start the sprint and work on the tasks
4. End the sprint and check what task where completed
5. Sum of the story points of completed is the velocity

Velocity is easier to estimate in the middle of the project when a few sprint have been completed due to having more historical data collected about he velocity.

Velocity measurements are only valid if the environment is stable. Factors such as replacing team members, changing the process, and changes to how the team sits will affect the velocity.

Velocity will generally more stable after a couple of sprints if the environment does not change and the work is done at a sustainable pace to avoid the team getting burned out.

As with all statistics it is easy to cheat and interpret the data in different ways, this holds for measuring velocity. It is important to have a clear definition of done for a story to know the real velocity. Being done can be that the product owner accept the user story as done or it can be that all the steps in a company defined process have been completed such as for example having .passing tests and having done a code review.

### Time Boxing

A time box is a fixed interval in time, for example the coming three weeks. Time boxing is the creation of plan for what to complete in an upcoming time box, can be to chose a number of tasks from a backlog estimated to be able to be handled in the available time.

Story points can be used when time boxing. Each task in the back log is assigned a number of story points. Assuming that the team have already completed some time boxes and that the it was tracked how many story points where completed so can it be known how many tasks to plan into the upcoming time box.

A release can be done at the end of the time box if the combination of tasks completed adds up to something that the client can use.

In Scrum a time box is known as a Sprint and time boxing is known as Sprint planning.

### Gantt Charts

Gantt charts is a type of bar charts used to visualize project schedule and progress. This type of chart also shows dependencies among the tasks.

The tasks are listed vertically to the left and then there is a timeline with time periods (can be weeks or sprints) at the top of the chart that stretches out from the task lists. The tasks to be completed first are placed first followed by tasks to be completed later. A bar for each task is placed on the time line part of the task. The length of the bar is proportional to the effort for the task.

Gantt charts will typically look like a stair case going down from lift to right. The project is finished when at the bottom of the stair case.

There are obvious similarities between the Gantt charts and the waterfall model but Gantt charts can be used in agile contexts as well but might need to be kept up to date more since scope and timing tend to change in agile development as the project evolves.

Gantt charts can be used for low-level task tracking as well as high level release tracking.

## Release Plans

Release plans shows the expected feature growth of a product at the end of a defined time box. The intended audience of the release plan is both the client and the developers.

## Module 3 Iteration Planning

Module 3 covers:

- Good estimates
- What affects estimates
  - The Cone of Uncertainty
- Approaches for creating estimates
  - Bottom-up
  - Analogy
  - Experts
- Calculate task estimation time by use of estimation formula
- Understand task dependencies
  - Start-start
  - Start-finish
  - Finish-start
  - Finish-finish.
- Critical path method (CPM) chart
- Concept of slack
- PERT chart
- Differences between CPM chart PERT chart
- Iteration planning
- Concept of planning as self-assigned work done by developers; not assigned by clients

### Task Dependencies

### Critical Path Method Chart

Critical Path Method (CPM) charts is a visual way to organize task dependencies. Task that are dependent are linked together to form paths. By adding the time estimates for each task it is possible to find the path that will take the longest time to complete, this path is called the critical path. The critical path is the shortest time the project can be completed in, assuming multiple team members that work in parallel on different paths.

### Pert Chart

### Iteration Plan

## Module 4 Risk Planning

### Antipatterns

Individual anti-patterns covered by lessons:

- Micromanagement
- Seagull management
- Email as the primary means of communication
- Loose cannons
- Intellectual violence

Originally the term loose cannon refereed to a cannon not tied down properly on a war ship causing it to roll away when fired causing havoc on the ship itself. The term loose cannon is today used as a term for an individual anti-pattern that refers to an unpredictable person in the team that make significant project decisions without consulting the rest of the team.

### Causes of Failures

### Risk Assessment Likelihood and Impact

### Risk Strategies Contingency Mitigation
