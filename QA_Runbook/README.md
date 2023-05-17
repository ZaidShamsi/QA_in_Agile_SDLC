# QA Runbook

To begin with, **testing is context dependent**. It depends on:
1. which Software development Life Cycle you have chosen for your project, which in turn depends on:
2. What is the nature of your project? Is it:
    1. a safety-critical system, for example, a nuclear power project. In this case taking an iterative approach for development is a risky endeavour. As the requirements in such a project are clearely defined and technology well-established, here, a V-model is best suitable.
    2. a short time to market project, for example, an e-commerce site. In this case since the requirements are fluid and time to market is the key factor an Agile SDLC is our best go. Now the question arises which agile are you?

## Kanban vs Scrum

**Kanban** methodology is governed by Just in Time (JST). As soon as a team member finishes the task, next task in line can be picked. Releases can be planned as and when we have developed and tested a deliverable. The Agile ceremonies in Kanban are:
1. Daily Stand-up Meeting (DSM): This is a short, say 15 minutes, call. The objective is to induce public accountability in each team member and for everone to give their updates on:
    1. What they have done.
    2. What they are planning to do next.
    3. Highlight blockers, if any.
    4. and share updates in general with the team.
3. User-Story Refinement: This can be a call/discussion between BA (Business Analyst), Developer, and QA.

(Here's an interesting read: JST has its origin in [Lean Manufacturing](https://en.wikipedia.org/wiki/Lean_manufacturing).)

In **Scrum** methodology, we have quantified deliverables that are to be delivered in fixed time interval called sprint length. Mostly, sprints are of two weeeks. Deliverables can be quantified based on Sprint Velocity. Releases usually happen near the end of sprint. The Agile ceremonies in Scrum are:
1. Daily Stand-up Meeting (DSM)
2. Sprint Refinement/Backlog Planning: It is advisable to spend atlest 2 hours each Sprint to groom the Backlog. The Agenda of this call is
    1. To move the high priority ticket up in the backlog.
    2. To discuss the new enhancements/tickets/bugs with team and take a call if they should be kept in the same Sprint or moved to next.
    3. To determine the Level of Effort (Effort estimation) for each ticket. This is usually done in terms of Story Points.
4. Sprint Retrospective: The Agenda of this call is to discuss:
    1. What went well? This we should **continue** doing.
    2. What went wrong? The we should **stop** doing.
    3. What can we do to improve the process? This we should **start** doing.

(Here's an interesting read: [Why is it called Scrum?](https://dzone.com/articles/scrum-whats-in-a-name))

The best practice for DSM is to keep it short. Complete a circle, let everyone give their updates and if any point on which discussion is required discuss it later in the parking lot. This gives opportunity to others to drop of the call and serves the purpose of DSM.

### Sprint velocity

Sprint velocity is defined as the number of story points that a team is able to cover in a sprint.

#### Story points

Let's continue with our example of an e-commerce site. Say, a requiremnt/ticket/user-story comes and client wants to include a feedback icon on each page. Now, when this ticket will be disucussed in refinement call, developer will give estimate of how much effort is required for this. Is this a heavy lift? or low effort? Now these efforts are measured in number of hours required to complete the task, and ususally they are converted into points called story points. So, for example, 1 story point can connote to 1 Business Day, which is 8 hours. This is just an example at the end it depends on what your team has agreed upon.

(Here's an interesting read: [Which agile are you?](https://www.atlassian.com/agile/kanban/kanban-vs-scrum))

## Table of contents

- QA Process
- Functional testing
- Regression testing vs Retesting
