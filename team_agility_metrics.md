# Possible Team Agility Metrics

It's best to approach all below metrics as _indicators_ i.e. they may or may not suggest an underlying problem and therefore should not be taken at face-value.

Metric | Theme | Calculation | Purpose
------ | ----- | ----------- | --------
Average time of open pull requests | Delay | N/A | Indicates whether there may be a queue and therefore a bottleneck in the development process
Scope change | Stability, loss of focus | N/A | Percentage of unplanned tasks added or removed from sprint compared with forecasted. (All unplanned tasks should be estimated before being put in the sprint)
Ratio of velocity | Sustainable pace | Number of average completed tickets/ number of average forecasted * 100 | N/A
Work-type distribution | Focus imbalance | Total number of tickets of each type in the current sprint displayed as a pie chart | Percentage of sprint work that is: `Bugs`, `Technical work`, `Product work` or other type of choice. Indicates which types of work the team is focusing on for the sprint and whether there is an imbalance towards technical or product work for example.
Epic distribution | Priorities, focus | Percentage of total sprint work (story points) by epic | Indicates which topics the team’s focus and efforts are for the sprint.
Backlog time | Delay, loss of focus | Number of backlog items * median cycle time | Indicates how long it would take the team to complete all items in their backlog. The longer this is the more unrealistic, irrelevant and wasteful the size of the backlog is.
WIP ratio to team member | Delay | Number of items in progress/ number of team members | Ideally should not be over 1. If it is, there is a higher chance of multi-tasking and therefore waste occurring. Tickets will likely be taking longer to finish as a result.
QA Lapse | Delay, 'built-in quality' | Average number of times a ticket was sent back to development from QA. (Could also check ‘First Time Pass’ instead) | Indicates lack of quality being implemented - possible reliance on QA to detect issues - more time needed on rework.
Median cycle time | Development pace | Little's Law | Overall time it is taking developers to start and finish a ticket. A higher number here indicates there could be a high WIP, queues/ bottlenecks, and other inefficiencies in the development process.
Median lead time | Time-to-market pace | N/A | Overall time it is taking a ticket to be delivered from the moment it is created. A higher lead time suggests the presence of waste and one of the first places to look is the backlog*.
