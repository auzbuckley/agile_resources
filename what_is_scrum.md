# What is Scrum?

Scrum is an agile framework that supports  (not solves):

* Protecting the team from disturbances/ keeping them focused
* Encouraging team responsibility, autonomy and team work
* Cutting work into small, valuable deliverables
* Continuous Delivery
* Limiting work in progress (stop working on so many things at once.)
* Encouraging transparency through high visibility, simplicity and regular/ predictable cadence
* Cyclical inspection and adaption (continuous improvement)

:bulb: _It's recommended to take a look at [the scrum guide](https://www.scrumguides.org/scrum-guide.html) itself to understand more about scrum theory, values, the scrum team, scrum events and artefacts.  Warning: it is long/ wordy._

_The guide does a pretty good job, so it's contents won't be reiterated in detail here._

_However there are some extra 'pearls of wisdom' regarding Scrum which are important to know/ understand, which will be outlined below._

## Scrum 'Tips'

### :white_check_mark: Scrum process should never impede team progress

One of the functions of a Scrum Master is to always ensure that the processes in Scrum do not prevent the team from moving forward. Some of the biggest complaints refer to the time spent in scrum meetings or 'ceremonies'. Often if you find that sprint planning, standup or the retrospective etc. are wasting your time, taking too long or causing unnecessary overhead chances are that scrum has either revealed a deeper problem to you, or you might not be running the meeting as intended. See the tip below.

With a two week sprint (80hrs) you are looking at anywhere from 6-11% of that time being in a scrum 'meeting', be it standup, retro or other. Most of this time is at either end of the sprint.

### :white_check_mark: Beware Scrum as 'Cargo Cult Agile'

Scrum is an agile framework - that is it is a supporting structure for interacting with a larger idea (agile). Much like Django is a supporting structure for interacting with the web (therefore called a web framework).

Many teams apply 'scrum practices' and expect that this will make them agile, but this is not the case.

Scrum is simply a set of practices that first appeared as the result of teams being agile. If your team tries to apply these practices without understanding the reasoning behind them and without having an 'agile' ethos, at best it is very likely your team will not get the expected results, at worst it can lead to a significant drop in performance. This is what has been called ['Cargo Cult Agile'](https://www.jamesshore.com/Blog/Cargo-Cult-Agile.html).

Therefore, it is entirely possible to do scrum, and still not be agile e.g. you can have retrospectives but not execute your action points; you can have daily stand ups but no one listens to each other; you can have sprints but not produce a potentially shippable product increment at the end etc. etc.

Nevertheless, because of the boundaries that it provides, Scrum can be a good place to start when trying to become more agile, as long as efforts are made to understand why and not fall into blind adherence to the 'rules'. At the end of the day, what practices you use is not as important as why you are using them.

### :white_check_mark: Scrum does not solve your problems. It will make them transparent.

If you employ Scrum in its entirety you should be ready to deal with the problems that it will reveal. Unless your organization is prepared to support agility, 'proper' Scrum is likely make people uncomfortable, maybe even upset. It requires unlearning old habits and learning new ones. It may not be directly compatible with your current culture and environment, and can be very jarring.

Some organizations choose to use only certain parts of Scrum, and ignore other parts that are perceived to either not fit context, or reveal problems the org is not ready to deal with. This kind of implementation is often referred to as 'Scrumbut', but does not necessarily need to be associated with a negative connotation. The goal should not be to implement Scrum. Scrum should be just a means to an end.

### :white_check_mark: The team over the individual

There is no "I" in "Team", or so the cliche goes. Scrum purposefully _does not distinguish_ between members of the development team. Whether it is a QA, developer, team lead etc. It places the emphasis on the team, not the individual and encourages team collaboration to get things done. This means, for example, that if the QA is overloaded, then a developer should step in to help test; if a developer finishes their task they should offer help to other developers who still have tasks in progress; and that the team in general should avoid bus factors and information silos.

:warning: _This does not mean that everyone on the team must be a generalist. It simply means, that for the benefit of the team, you are expected to develop [T-Shaped skills](https://en.wikipedia.org/wiki/T-shaped_skills) and not remain siloed in your own discipline._

### :white_check_mark: Scrum teams are intended to be cross-functional

Cross-functional teams are described by the Scrum guide as having "... all competencies needed to accomplish the work without depending on others not part of the team." This is a practice that developed out of several agile principles, most notably: 
building projects around motivated individuals by giving them everything they need to get the job done, including trust, and;
continuous and frequent delivery of valuable and working software (with a preference to the shorter timescale e.g. weeks not months)
Depending on the project, a component team (i.e. a team that only has a specific skillset such as a Backend team, Frontend Team or Quality Assurance team) usually do not themselves possess everything needed in order to deliver an increment of software valuable to the customer. They instead are only one part of the product/ feature and rely on the combined efforts/ skills and cross-team collaboration in order to deliver to the customer. Producing a 'Potentially Shippable Product Increment' by the end of the sprint is central to Scrum's built in customer feedback cycle (and agile principles).

This is not to say however that Scrum practices won't benefit a component team, however they will likely have to adapt the framework to suit.

:warning:
* _Having multiple component teams working on parts of a single feature naturally creates dependencies and reduces autonomy, dependencies create collaboration/ communication and management overhead, slowing the time to delivery down significantly. Try to minimise the amount of sequential development (and therefore hand-overs) between teams if you cannot have cross-functional teams._
* _The end-user feedback loop is often significantly longer with component teams seeing as it usually takes more time for the integrated project to be released. This means learning and experimenting rapidly becomes more difficult, and the purpose of 'iterations' becomes diluted._
* _Component teams arguably still have their place, such as in SRE/ infrastructure teams, but it's recommended the ratio is weighted towards cross-functional teams._

### :white_check_mark: The development team decides how much to work on

The amount of work accepted into the sprint backlog (from the Product Backlog) is the decision of the development team. The Product Owner has responsibility over the content and priority of the Product Backlog (and therefore by default what the team can choose to work on) but cannot dictate how many work items the team accepts for the sprint backlog.

If new work needs to be brought in during the sprint, it can only be done so on agreement by the development team. The scrum guide literally states that _"Only the Development Team can change its Sprint Backlog during a Sprint."_ This means the development team has the right to reject new work if the PO does not have a convincing reason why to add it. 

:warning: _This should not turn into 'development team vs Product owner', but a discussion that takes place openly and transparently. If a new item must be added during a sprint, the consequences/impact it will have on the original sprint goal and on-going work must be considered._

_The reason for this 'rule' is that the development team knows best how much they can work on over a given period of time._

### :white_check_mark: Scrum does not define everything

There are a few things mistakenly associated with Scrum, but which Scrum does not actually define, these include but are not limited to:

* Ticket 'types' e.g. bugs, spikes, user stories etc. - it simply refers to tickets as Product Backlog Items (PBI)
* Story points
* Velocity
* Burndown charts
These are 'emergent' practices that have become popular over the years but are not officially part of the Scrum framework.

Scrum also doesn't specifically tell you how to manage the backlog, how to scale, and maybe even places too much emphasis on predictability.

### :white_check_mark: Keep the focus

Sprints are designed to give teams a specific amount of dedicated time in order to get something done. In order to achieve their goal it is the job of the PO and the Scrum Master to ensure that the team is not distracted by external requests or influence.

This means that the scope of the sprint, ideally, is not changed during the sprint.

In reality though, there will be times where there is no choice but to add new tickets to the current sprint. However every effort should be made to keep these situations to a minimum. The development team must be critical of any new task being added, yet be able to adapt should scope change be necessary. If scope changes so significantly that the sprint goal is jeopardized, it is often advised to cancel the sprint.

:bulb: _If you do find your team in a situation where scope change is becoming an issue, [this post](https://medium.com/agilelab/strategies-for-handling-unplanned-work-during-sprint-2f89697509ff) offers useful tips on how teams can handle unplanned tasks._
