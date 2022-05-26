# Agile Foundations

> This page references content from the *Mountain Goat Software* site. It's an excellent resource and highly recommended!
>
> https://www.mountaingoatsoftware.com/agile
>
> Copyright ©1998-2022 Mountain Goat Software. All Rights Reserved.

**Contents**
- [Scrum Roles](#scrum-roles)
- [Scrum Artifacts](#scrum-artifacts)
- [Scrum Ceremonies](#scrum-ceremonies)

## Scrum Roles

- Product Owner
    - The product owner is the project's key stakeholder. Typically, the product owner will be the primary user of the product, or at least have a deep understanding of who will. Despite this expertise, the product owner does not get to determine how much work happens in the sprint cycles, or alter the goals for that sprint. Product owners must be available to the team, and engage actively with it. Communication is a huge part of this, as the product owner communicates with both the team and other stakeholders.
- Scrum Master
    - The Scrum Master is the person who ensures the team keeps to the values and practices of Scrum, sort of like a coach. They remove impediments, facilitate meetings and work with product owners. Interestingly, the Scrum Master is a servant-leader who doesn't have authority over the team, but does have authority over the process. They can't fire people, but they can alter how long the sprints are. This can make the role more challenging than a traditional management role.
- Development Team
    - The Development Team is a collection of individuals working together to develop and deliver the requested and committed product increments. It consists of cross-functional members who are capable of achieving the sprint goals. This could include software engineers, architects, programmers, analysts, system admins, QA experts, testers, UI designers, etc.

> https://www.mountaingoatsoftware.com/agile/scrum/roles

## Scrum Artifacts

- Product Backlog
    - The Product Backlog is the complete list of the functionality that remains to be added to the product. The product owner prioritizes the backlog so the team always works on the most valuable features first. The most popular and successful way to create a product backlog using Scrum methodology is to populate it with *user stories*, which are short descriptions of functionality described from the perspective of a user or customer.
- Sprint Backlog
    - The Sprint Backlog is the list of tasks the team needs to perform in order to deliver the functionality it committed to deliver during the sprint.
- Burndown Chart
    - Burndown charts show the amount of work remaining either in a sprint or a release, and are an effective tool in Scrum software development to determine whether a sprint or release is on schedule to have all planned work finished by the desired date.

> https://www.mountaingoatsoftware.com/agile/scrum

## Scrum Ceremonies

### Sprint Planning

*Attendees: Scrum Master, Product Owner, Development Team*

**Purpose:**

- Define the sprint goal.
    - A sprint goal is a short, one- or two-sentence, description of what the team plans to achieve during the sprint. It is written collaboratively by the team and the product owner. The following are example sprint goals on an e-commerce application:
        - Implement basic shopping cart functionality including add, remove, and update quantities.
        - Develop the checkout process: pay for an order, pick shipping, order gift wrapping, etc.
- Create a sprint backlog.
    - The sprint backlog is the other output of sprint planning. A sprint backlog is a list of the *product backlog* items the team commits to delivering *plus* the list of tasks necessary to delivering those product backlog items. Each task on the sprint backlog is also usually estimated. User stories are generally estimated in story points while individual tasks are estimated in hours.

**INVEST** principles are used to ensure items are ready to be brought into a sprint. An item can't be brought in without satisfying all of these:

- Independent - of all other tasks. If dependency exists, these must be split out
- Negotiable - not a specific contract for features
- Valuable - provides business value
- Estimable - if an item isn't estimable, it needs to be split or refined until it becomes estimable with at most 8 story points
- Small - must be completed in one sprint
- Testable - in principle (a test strategy doesn't need to exist) but it must have clear acceptance criteria and hypothesis to test

> https://www.mountaingoatsoftware.com/agile/scrum/meetings/sprint-planning-meeting

### Sprint Review (Demo)

*Attendees: Scrum Master, Product Owner, Development Team*

**Purpose:**

In Scrum, each sprint is required to deliver a potentially shippable product increment. This means that at the end of each sprint, the team has produced a coded, tested and usable piece of software. So at the end of each sprint, a sprint review meeting is held. During this meeting, the Scrum team shows what they accomplished during the sprint. Typically, this takes the form of a demo of the new features.

During the sprint review, the project is assessed against the sprint goal determined during the sprint planning meeting. Ideally, the team has completed each product backlog item brought into the sprint, but it's more important that they achieve the overall goal of the sprint.

This feedback loop within Scrum software development may result in changes to the freshly delivered functionality, but it may just as likely result in revising or adding items to the product backlog.

In general, a sprint review should not be used by a team to get formal sign-off on their work from their product owner. The team and product owner should be working so closely during a sprint that the team knows what the product owner thinks of what they've built. Also, it’s possible that the product owner needs to wait to fully accept something until other stakeholders have a chance to comment on the work.

> https://www.mountaingoatsoftware.com/agile/scrum/meetings/sprint-review-meeting

### Sprint Retrospective

*Attendees: Scrum Master, Product Owner, Development Team*

**Purpose:**

The sprint retrospective ceremony is a time for team members to consider how to improve their way of working. This means they may change aspects of how they do Scrum, such as the length of their sprints. But a retrospective can also cover general aspects of working together, such as whether to ban morning meetings or which topics are appropriate to discuss on Slack and which require a face-to-face conversation.

The sprint retrospective should be attended by the whole team—that is, the development team, Scrum Master, and the product owner. To do otherwise is to create a schism within the team. A good agile team should avoid any behavior that leads to an us/them mindset.

Typical questions:

1. Start doing?
2. Stop doing?
3. Continue doing?

> https://www.mountaingoatsoftware.com/agile/scrum/meetings/sprint-retrospective

### Daily Scrum Meeting

*Attendees: Scrum Master, Product Owner, Development Team*

**Purpose:**

In Scrum, on each day of a sprint, the team holds a daily scrum meeting called the "daily scrum." Meetings are typically held in the same location and at the same time each day. Ideally, a daily scrum meeting is held in the morning, as it helps set the context for the coming day's work. These scrum meetings are strictly time-boxed to 15 minutes. This keeps the discussion brisk but relevant.

The daily scrum meeting is not used as a problem-solving or issue resolution meeting. Issues that are raised are taken offline and usually dealt with by the relevant subgroup immediately after the meeting. During the daily scrum, each team member answers the following three questions:

1. What did you do yesterday?
2. What will you do today?
3. Are there any impediments in your way?

By focusing on what each person accomplished yesterday and will accomplish today, the team gains an excellent understanding of what work has been done and what work remains. The daily scrum meeting is not a status update meeting in which a boss is collecting information about who is behind schedule. Rather, it is a meeting in which team members make commitments to each other.

> https://www.mountaingoatsoftware.com/agile/scrum/meetings/daily-scrum

### Backlog Activities

- Product Backlog Refinement
    - Product backlog refinement refers to ensuring the items at the top of the product backlog are ready for the next sprint. This can include adding detail to existing items, estimating, deleting items, adjusting priorities, splitting product backlog items to better fit within a sprint, and creating new items.
    - *Attendees: Scrum Master, Product Owner, Development Team*
- Product Backlog Prioritization
    - Before a new sprint begins, the product owner ensures the top of the product backlog has been prioritized.
    - *Attendees: Product Owner with input from stakeholders*
- Product Backlog Estimating
    - As noted above, many teams will estimate during product backlog refinement meetings. That is the ideal approach, and is possible if the entire development team participates in backlog refinement. If only a subset of the development participates in backlog refinement, team members will meet once per sprint to estimate any new work for which the product owner may need an estimate.
    - *Attendees: Scrum Master, Product Owner, Development Team*

> https://www.mountaingoatsoftware.com/blog/what-happens-when-during-a-sprint