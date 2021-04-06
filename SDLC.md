## Folloze development project lifecycle
### Motivation
We’re working in a rapidly changing environment, with many requests for product innovation and adaptations.
As professionals we are expected to give accurate time estimations, provide the product team with the ability to make smart decisions that result in a great user experience under the time constraints.

Our SDLC goals are to:
1. Work less on developers task reassignment
2. Make our quarterly product plan less sensitive to minor delays in project releases
3. Involve QA and product earlier in the process
4. Support a backlog of tasks to respond to customer requests
5. Handle the growing backlog of support tasks

### SDLC definitions
Watch [this video](https://www.youtube.com/watch?v=ATpJBeuknaQ) (until 16:30) to understand where we were inspired from
1. We work in a 2 weeks cycle with the following roles
    - ***Cycle Owner*** - Keeping the team from context switches. Handles all the unexpected issues, manages standups and looking at all the system errors - [read more](https://github.com/zvikamenahemi/handbook/blob/main/cycle-owner.md)
    - ***Backlog Owner*** - performs minor/small tasks/bugs of up to 6 development days. This backlog is updated by the product team before each cycle.  
    \* Sundays helping the cycle owner to clear the unexpected list
2. Medium/Large projects will always be split into two periods
   - **Release period** - 
     - 75% of the project
     - The period ends with a release to production*
     \* there might be multiple releases during the period
     - During the period the developer has two ways to make sure the feature is release on time
       1. ***Variable Scope*** - at the beginning of the project the developer is required to break the feature into tasks and provide time estimations for each task. This breakdown will be reviewed together with the product manager and the scope of the release will be adjusted accordingly by priorities.
       2. ***Technical Debt*** - decide together with the manager to mark some things as technical debt that will be addressed in the post release phase. It can be issues identified in the code reviews that will require too much time to fix or design choices that fit better the time available for the project.
   - **Post Release period**
     - 25% of the project
     - At the beginning of the phase technical debt is prioritized
     - This phase is all about cleaning after ourselves (fixing technical debt) and handling unexpected bugs
## Milestones
![wireframe](https://images.folloze.com/image/upload/v1617476412/milestones_ccgrs6.png)

1. **Concept Definitions**
   - *Owner* - PM 
   - *Outcomes* - definition doc including: 
     - Motivation
     - Use cases and user flows
     - Invision UX and UI flows ready for the developer and QA to review and execute 
     - Scope and clear priorities 
     - A meeting with PM groups and tech leads should be held to sync and align on scope, priorities and focus areas before the kickoff meeting
2. **Project Kickoff**
   - *Owner* - PM
   - *Participants* - PM, developer, UX, QA and tech manager
   - *Timing* - first day of the cycle, at latest.
   - *Goal & Outcomes*
     - Review the definitions, flows and UI
     - Define priorities
     - Scoping to sub features (if possible/needed)
     - Open issues
3. **Dev Design Review**
   - *Owner* - Developer
   - *Participants* - developer and tech manager
   - *Timing* - at ~10% of the feature planned time after the developer did a breakdown and gave time estimations
   - *Goal & Outcomes*
     - Technical solution is clear
     - Uncertaintiees are identified
     - Time estimations should be communicated to PM and QA 
4. **Test Plan Review**
   - *Owner* - QA
   - *Participants* - QA, PM, UX, developer and tech manager
   - *Timing* - at ~25% of the feature planned time 
   - *Goal & Outcomes*
     - Reviewthe test plan
     - Make sure all requirements and use cases are covered
     - Make sure expected behaviour is clear
     - Map gaps in the test plan needed to be fixeed
5. **Weekly Status**
   - *Owners* - PM and developer 
   - *Participants* - PM, developer, UX, QA and tech manager (optional)
   - *Timing* - On a weekly basis from the kickoff until release
   - *Goal & Outcomes*
     - Status update
     - Open issues
     - Risks
     - Communicate and update the team in Slack channel and definition doc / Invision  
6. **Handover to QA** (complete feature or per sub-feature)
   - *Owner* - Developer
   - *Participants* - Developer, QA
   - *Timing* - at ~65% of the feature planned time 
   - *Goal & Outcomes*
      - Structure handover from dev to QA
      - Scope is clear
      - Feature is ready to be tested 
7. **Release** :dancer:
8. **Post Release**
   - *Owner* - PM
   - *Timing* - after release
   - *Goal & Outcomes*
     - Manage the feedback and bugs
     - Communicate urgent bugs to the developer and add the others to a backlog list based on priority 
     - A summary and retrospective meeting should be held in relevant cases
     - *Participants* - PM, developer, UX, QA and tech manager

