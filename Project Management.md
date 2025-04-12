---
aliases:
  - project management
tags:
  - management
  - project
source: 
source page: 
priority: 
author: "[[Hendrix Gryspeerdt]]"
---
# [[Project Management Tutorial]]

## Basic project management process
1. figure out project scope (what are all the things to do) (project dictionary)
2. break down project scope into reasonable sized subtasks (work breakdown structure) 
3. estimate duration to complete each subtask - (PERT Method $T_{Estimate}=\dfrac{T_{Optimistic} + 4T_{\text{Most Likely}} + T_{Pessimistic}}{6}$)
4. determine dependencies between subtasks
5. use critical path method to create project network diagram
6. assign responsibilities and allocate resources
7. put project into gantt chart to figure out timeline
8. use kanban to keep track of smaller day-to-day subtasks
9. update gantt chart and CPM times when you have new estimates

## Project Management from [[ELEC390 - Principles of Design and Development|ELEC390]]
Gantt charts, compared to other tools for project management, has its strengths and weaknesses.  
A critical path method (CPM) chart is typically used first during the initial planning, and the Gantt chart and Kanban board are used for the remainder of the project. 
Often, the Gantt chart is simultaneously used with the Kanban board at different scales: 
the Kanban board denotes sub-tasks that work towards the completion of tasks on the Gantt chart and changes faster, 
whereas the Gantt chart is re-evaluated at a slower pace (perhaps weekly). 
In many cases, project management software includes both of these tools in a single product. 


The usual steps in the project management process are as follows: 
1. Identify all the major tasks involved in the project and estimate their durations.
2. Determine dependencies between tasks and use a CPM chart to sketch the task relationships.
3. Determine the critical path from the CPM chart. 
4. Assign responsibilities from the tasks and allocate resources.
5. Prepare a Gantt chart based on the dependencies from the CPM chart and the responsibilities determined above. 
6. Use a Kanban to keep track of smaller, day-to-day sub-tasks that make up a task on the Gantt chart. 

Once the charts are prepared, the project management work is not done. 
The Gantt chart is a working document that evolves with the project and embodies the strategy that the team is using to complete the project. 
It, and with the Kanban board, needs to be in a manageable and easy-to-update format, or it will soon become useless. 
It is very important to understand that projects are fluid and that things will inevitably change as the project progresses. 

Generally speaking, most novice project managers and designers are overly optimistic about the time required to complete work and often tend to fall behind schedule. 
The Gantt chart and Kanban boards should be updated as things change to ensure that the project completion deadline can still be met such that all team members see and work on the appropriate tasks at the appropriate time. 
If there is not enough time to finish the project as originally planned, adjustments to the project (such as changes to the project scope or deliverables) must be made for the remaining tasks. 
One tool that might be helpful to prioritize tasks when resources are limited is Pareto analysis. 

# Diagrams
- [[Project Management Process.canvas|Project Management Process]]
    - [[Project Stakeholders]]
## To consolidate 
- on hendrixg10@gmail.com see “Agile Meetings”
- Book: “Visualizing Project Management: Models and Frameworks for Mastering Complex Systems”
- Book: “How to Manage Complex Programs: High-Impact Techniques for Handling Project Workflow, Deliverables, and Teams” by [[Tom Kendrick]]
- Book: “From Projects to Programs: A Project Manager’s Journey” by [[Samir Penkar]]
- Book: “Governance of Portfolios, Programs, and Projects: A Practical Guide” by [[Hendrix-Note-Share/Project Management Institute]]
- Book: “Program Management Leadership: Creating Successful Team Dynamics” by [[Mark C. Bojeun]]
- Book: “Transforming Business with Program Management: Integrating Strategy, People, Process, Technology, Structure and Measurement” by [[Satish P. Subramanian]]
- Book: “Sustainable Program Managemen” by [[Gregory T. Haugan]]
- Book: “The Self-Made Program Leader: Taking Charge in Matrix Organizations” by [[Steve Tkalcevich]]
- Book: “Managing Complex Projects and Programs: How to Improve Leadership of Complex Initiatives Using a Third-Generation Approach” by [[Richard J. Heaslip]]
- Book: “Stakeholder Engagement: The Game Changer for Program Management” by [[Amy Baugh]]
- Book: “Successful Program Management: Complexity Theory, Communication, and Leadership” by [[Wanda Curlee]] and [[Robert Lee Gordon]]

## How To based on [[Elon Musk]]
This he mentioned in a podcast with [[Lex Friedman]] during August 2024 (podcast number 438).
1. Generate initial requirements
2. Make requirements less dumb by questioning their necessity
3. Generate design/solution
4. For each component of the solution, theorize what would happen if that component were removed, ask: does the solution still meet the requirements (if yes, get rid of it)? If the solution does no longer meet the requirements, can the remaining components be altered such that they meet the requirements?
5. After step 4 is repeated multiple times, try to optimize the best solution to better exceed the requirements.
6. Any given thing/process can be sped up. You shouldn’t try to speed it up if it shouldn’t exist (didn’t delete enough basic stuff). Speed up the process as much you can.
7. Once you have sped it up as much as possible, try to automate it.

Whatever the frontline people are doing, I try and do at least a few times myself. I did some compute cluster cabling.
# How to, based on [[CIBC Enterprise Delivery Framework]]
- Your initial stakeholder contacts you saying "something about my current state could be better, and I want you to help me resolve this issue", your next step is to determine (if the stakeholder doesn't know the answer to a question, ask, "who can I speak to to get an answer to this question?" If not all questions get answered, schedule a follow up meeting to continue answering questions in more detail) : What do they value (saving time, money, employee experience, ...)?, What is their current state (Current state [[Process Map]], Current costs, current cycle times, current ...)?, What about their current state is "bad"?, What can be done to change the current state to something better (High-Level Business Objectives)?, What does the ideal future state look like (High-Level Business Benefits)?, What will it take to get to that ideal future state (Costs, timelines)? Do the costs of enacting the change become outweighed by the benefits in the future state (cost-benefit analysis, payback period, return on investment, [[The Internal Rate of Return]], likelihood of achieving benefits)? Is there an alternative [[Change Endeavor]] that we could focus on and produce higher returns? Do we proceed with determining specific actions/activities required to enact this [[Change Endeavor]] (yes/no, if yes -> proceed to next set of questions)?
- before deciding to proceed with the [[Change Endeavor]], you need to have a [[Project Management Plan]]
- Once you have decided to proceed with the [[Change Endeavor]], you need to determine (more concretely) what are the: objectives, deliverables, work packages (grouping of related deliverables), timelines, stakeholders, action items. Then you separate the project into work packages with the grouped deliverables (work packages are disjoint sets that comprise 100% of the activities to be completed, ideally stakeholders' responsibilities lie within the fewest number of work packages possible). Then you treat each work package as a new [[Change Endeavor]] and recursively repeat the same questions to determine objectives, deliverables, work packages, timelines, stakeholders, and action items. Then you create a work plan to get stakeholders to agree on the work to be done for the project and the timelines to do so.
- Once you have a work plan and you want to implement work packages into the business, you need to prepare a Business Implementation Plan. This plan contains
	- implementation strategy which takes into account pre-conversion, conversion, and post-conversion planning (conversion = change or implementation) contains: Assumptions and Dependencies; Readiness Criteria; Success Criteria.
	- detailed day-by-day (or even hourly) schedule for implementation activities: summary/list of key checkpoints and go/no-go decision points (outlines all decision checkpoints throughout the life-cycle of the implementation. Indicate who must be in attendance and how you will document and communicate decisions); pre-implementation activities; implementation activities, post-implementation activities; implementation support team (objectives of support team, list of team members and their role); escalation procedures; blackout strategy; contingency strategy; issue management and escalation process
- [[Project Management Productivity]]
- Use a [[RAID Log]] as the Project Management Log
- have a problem you want to solve, that problem is an effect which has a cause, it occurs over time. determine the entire process by which that problem comes about. Identify all cause and effect relationships.
- have a [[Business Process Model]] to define the current state of business for the project
- have a list of benefits that would result in solving the 
- Define requirements for the project (what attributes would the improved future state have?) these form the project L1 [[hypothesis]]!!
	- ![[image 42.jpg]]
	- ![[image 43.jpg]]
	- ![[image 44.jpg]]
- Have a desired future state [[Business Model]] or [[Mission Model]]. This is the prediction your L1 [[hypothesis]] is making.
- figure out what has to change, actions to be taken, to go from current state to future state. This is your second [[hypothesis]]. “If we do this and this and this to the current state [[Business Process Model]], then we will result in the future State [[Business Process Model]].”

# Related Documents - old stuff 
- Flowchart illustrating how to [[Organizing a High-Performance Team.canvas|Organize a High-Performance Team]] - does not work
- For managing tasks: 
    - [[template-task-list_2024-01-18.xlsx]]
    - [[RACI Model]]
- For planning meetings (Agendas): [[template-meeting-agenda_2024-01-18.xlsx]]
- Example of Team/Company Strategies:
    - [[QSCCT Strategy.canvas|QSCCT Strategy]] and [[QSCCT Strategy Simple.canvas|QSCCT Strategy Simple]]
- 