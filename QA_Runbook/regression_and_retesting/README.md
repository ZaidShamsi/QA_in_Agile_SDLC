Consider a scenario that you are assigned as a QA Tester to a ticket. This ticket can be:
- a user-story
- a task
- a bug
- an enhancement, or anything in between

In simple jargon, you are given a task to test a component. You tested it and you found bugs. Great job! :). Then, this component will go back to developer he will fix the bug and will move it back to you. Now here, when you will start testing the component again, you will be testing:
1. the bug (this is the changed area of the component) and
2. the remaining component, that is, the existing functionality which was working fine (this is the unchanged area of the component).

So, Pt #1 is called re-testing or confirmation testing and Pt #2 is called regression testing.

**The objective of retesting is:**
- to ensure that the fix provided confirms the specified requirements and is working as expected.

**The objective of regression testing is:**
- to ensure that the component has not degraded/regressed to lower quality, that is, new defects are not introduced in the unchanged area and
- to detect the masked defects that might have now become unmasked.
