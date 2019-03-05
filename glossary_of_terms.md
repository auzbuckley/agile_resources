# Common terms from agile product development

:warning: _Scrum terms are marked with a_ :star:

## Product Backlog Item (PBI) :star:
Any item on the product backlog - also can simply be referred to as a 'ticket' in some organizations.

## User Story
A lightweight, high-level description of a customer-centric feature that:
- Specify the ‘who’ + ‘what’ + ‘why’ and any acceptance criteria (AC)
- Are triggers for conversation, not definitions of requirements
- Are usually no bigger than a few days worth of work
- Represent a thin vertical (touches multiple layers) slice of deliverable functionality that provides some benefit to the end-user and is a potentially shippable product increment e.g. is ideally standalone and can be demoed and used by the user on its own for optimal feedback

:warning: **Warning**:
- _Stories evolved out of a need to avoid getting bogged down in formal requirements analysis and documentation. They are high level and do not specify any technical implementation detail_
- _The format “As a … I want … So that …” helps keep focus on the 'who, what and why', enables consistency in story description and helps to avoid later confusion, but it can also be easily misused._
- _If it is not exposed to the end-user, and/or does not provide clear value to the end-user (from their perspective) then it is generally not considered a user story. The end-user therefore must be defined._
- _Stories are often implemented by more than one person (via sub-tasks)._
- _If a user story is too big, be careful that the smaller stories created from it continue to meet the definition above and are not are actually tasks trying to be stories…._
- _Not all Product Backlog Items (PBIs) are stories. Some can be bugs (found in released code), others can be technical tasks not associated with any story (have any direct customer benefit/value), such as infrastructure tasks, refactoring etc. These types of ticket do not have to be written in 'story' format and probably make more sense to write in domain language._
- _Not only are user stories hugely beneficial to non-technical stakeholders, their simple, short format are supposed to act as an 'information radiator' that anyone can read and understand._
- _Placing a focus on the the end-user also helps develop valuable acceptance tests i.e. UI tests or otherwise that check end-to-end usage scenarios (often examples of the Acceptance criteria) of the user story_

## Acceptance Criteria (AC)

- Normally included into a user story ticket
- Simple and short pass/fail statements that together describe the scope of the user story.

:warning: **Warning**:

_Gherkin syntax [given, when, then] is a popular way to describe AC, however it's helpful to understand that this actually describes scenarios which are, in theory, concrete examples of acceptance criteria. Gherkin syntax itself was developed as a BDD format for describing AC as behavioural scenarios that could be executed as automated acceptance tests. Similar to the format 'As a... I want... So that...', if misused, the syntax loses much of its value._

## Subtask

- A smaller division of a user story, that represents usually a technical step taken towards fulfilling the requirements (AC) of the user story (usually between 0.5 and 2 days to complete).
- They normally describe the technical ‘how’.
- They are normally only done by one person.
- They do not require any special formatting - they should be written in a language familiar to those who will implement it.

## Definition of Ready (DoR)

Explicit, visible and minimum criteria that a user story must meet in order to be accepted for a sprint.

## Definition of Done (DoD)

Explicit, visible and minimum criteria that a user story must meet in order to be accepted as 'done'.

## Spike

- A story or task aimed at answering a question or gathering information, rather than at producing shippable product
Represents risk
- They often correspond to user stories or techincal tasks with too much ambiguity — tickets where we need to do research before we can estimate.
- Each spike should address one clear question, and result in one clear answer. No vague spikes, with vague answers. Ideally they have a clearly specified outcome.
- In theory every story contains unknowns, risks - spikes should be used sparingly and for critical unknowns
- They are timeboxed

Spikes originated from Extreme Programming.

## Bug

A bug can be considered as any unexpected behaviour of previously specified and agreed upon requirements.

:warning: **Warning**:

_If a feature is deemed to be behaving unexpectedly, yet the expected behaviour/ use case was never specified in the implemented user story, then it is not considered a bug._

## Estimation :star:

- User stories are estimated in story points (usually fibonacci sequence)
- Story points represent relative effort and are used to group stories by similar size, not by finite time.
- Any story estimated to be 21 or above should probably be broken down though this depends on what this number represents per team.
- Every story should be evaluated as to how it can be broken down to its smallest possible size
- There is debate about whether a spike itself is estimatable. On the one hand it is work done during a sprint and could therefore be reflected in the velocity, however a spike is also something which should not drag on (for example if an estimate was too low) which is why others favour time-boxing.
- Sub-tasks of stories are usually not estimated but sometimes are in man hours.
- Like spikes, it is not common to estimate bugs, due to their uncertain nature, however it is up to the team to decide how they would like to approach such product backlog items.

:warning: **Warning**:

- _Story points are not from Scrum_
- _Estimates are exactly that - estimates. Do not dwell too much on them, your relative 'accuracy' will improve over time._
- _Generally its not a good idea to re-estimate tickets once work has started. This is mixing before knowledge with after knowledge and makes it far more difficult to compare tickets later._

## Velocity

Velocity is often considered as a measurement for tracking delivered customer value over a sprint, not the total amount of work done, but this is not officially defined. In this regard, it is common for only user stories and sometimes technical tasks to count towards the velocity. Bugs, spikes etc are therefore sometimes not estimated (also because they tend not to be easily estimatable) being arguably considered as not delivering direct customer value. This is a point of contention, and discretion is advised :)

The velocity should stabilise per sprint over time, and the average from preceding sprints can be used to gauge how much work can be realistically accepted in the next sprint, and even help determine if deadlines will be met.

:warning: **Warning**:

_Velocity should never be used as a metric to push for better performance e.g. setting a velocity 'target'. Performance in most cases should be tied to outcome, not output which velocity barely represents. Estimates are relative numbers and mean different things to different teams and can easily be manipulated to reach 'goals'._

_**Velocity should be treated as indicitive, not precise, so don't spend to much time paining over exact numbers.**_

_Whatever type of ticket you choose to estimate (user story, bug, technical task etc), understand what your velocity (or progress) represents and what this means for your team and anyone else who is interested in your work and make it clear._

## Product Backlog :star:

The Product Backlog is owned by the Product Owner. It contains mostly stories, but can also contain spikes as well as technical tasks not associated with any story, such as infrastructure tasks. During Grooming meetings, the items in the Product Backlog are refined as a team. However the PO can constantly add, remove and prioritize the items. The product backlog should _not_ be a 'bottomless pit' of PBIs - but this is another story.

## Sprint Backlog :star:

The Sprint Backlog contains the tickets that the team has accepted for the sprint and the tasks needed in order to achieve them. Ideally, no new stories should be added during the sprint to give the team optimal focus. The team however does not need to breakdown every story in the sprint backlog during Sprint Planning. Once there are enough stories broken up into tasks for a few days work the team can start working on those, while other stories can be broken down during the sprint.
