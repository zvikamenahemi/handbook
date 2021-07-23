## Cycle Owner

### Motivation
The cycle owner has three main goals:
1. Protect his team members' attention from context switches to allow them to be 100% concentrated on their features.
2. Allow quick turnaround for customers' issues. 
3. Make you an expert by improving your system knowledge, communication skills with different stakeholders within the company and build your sense of accountability.
The role enables Folloze to achieve its planned strategic goals without getting lost in the day-to-day tension of handling enterprise customers - and keeping them happy.

### Duties
As the name suggests, the cycle owner duty is for the cycle's length - 2 weeks.

#### The Support + Development board
The board contains tasks (requests from Support and CSMs) that the cycle owner needs to handle.
Managing the board is done by the support and product teams.
The board should contain only unexpected requests. Meaning there shouldn't be feature requests which the team could plan ahead of time.
The list is ordered by priority, and you should handle it in that order. Some of the cards are labeled by colors in order to indicate priority.

#### Daily Updates
In order to prevent communication gaps with Support, Product and CSMs the Cycle Owner should update in the end of every work day the tasks he has been working on and their current status. This should be done in the #daily-updates Slack channel.

#### Honeybadgers
Honeybadger is our run time error-monitoring system. Every new error is reported to the #alerts channel on Slack.
The cycle owner's responsibility is to triage the errors. 
**How to triage:**
1. New alert on Slack.
2. Acknowledge you are on it through the channel (open a thread for the alert's message).
3. Click on the alert to open it in Honeybadger.
4. Investigate the root cause and triage:
    - Ignore (timeout due to servers restart) - resolve the alert.
    - Bug - prioritize with the manager and add to Trello.
5. Write the plan of action inside the alert's thread.
6. Once the bug is deployed, resolve the alert in Honeybadger.
