# QA Runbook

Testing is context dependent. It depends on:
1. Which Software development Life Cycle you have chosen for your project? Which in turn depends on:
2.   What is the nature of your project? Is it:
        1. Helloa safety-critical system, for example, a nuclear power project. In this case taking an iterative approach for development is a risky endeavour. Even it does not make sense to take iterative approach here as the requirement in such a project are clearely defined and technology well-established. Here, a V-model is best suitable.
        2. a short time to market project, for example, an e-commerce site. In this case since the requirements are fluid and time to market is the key factor an Agile SDLC is our best go. Now the question arises which Agile are you?

## Kanban vs Scrum

**Kanban** methodology is governed by Just in Time (JST). As soon as a team member finished the task, next task in line can be picked. Releases can be planned as and when we have developed and tested a deliverable. The Agile ceremonies in Kanban are:
1. Daily Stand-up Meeting (DSM): This is a short, say 15 minutes, call. The objective is for everone to give their update on:
    1. What they have done.
    2. What they are planning to do next.
    3. Highlight blockers, if any.
3. User-Story Refinement: This can be a call/discussion between BA (Business Analyst), Developer, and QA.

In **Scrum** methodology, we have quantified deliverables that are to be delivered in fixed time interval called sprint length. Mostly, sprints are of two weeeks. Deliverables can be quantified based on Sprint Velocity. Releases usually happen near the end of sprint. The Agile ceremonies in Scrum are:
1. Daily Stand-up Meeting (DSM)
2. Sprint Refinement/Backlog Planning: It is advisable to spend atlest 2 hours each Sprint to groom the Backlog. The Agenda of this call is
    1. To move the high priority ticket up in the backlog.
    2. To discuss the new enhancements/tickets/bugs with team and take a call if they should be kept in the same Sprint or moved to next.
    3. To determine the Level of Effort (Effor estimation) for each ticket. This is usually done in terms of Story Points.
4. Sprint Retrospective: The Agenda of this call is to discuss:
    1. What went well? This we should **continue** doing.
    2. What went wrong? The we should **stop** doing.
    3. What can we do to improve the process? This we should **start** doing.

Here's an interesting read: [Which agile are you?](https://www.atlassian.com/agile/kanban/kanban-vs-scrum)

# QA Process (Work in Progress)

QA should actively participate in Agile ceremonies

1. When the sprint starts, QA should actively star
