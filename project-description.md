## Project Description

We're building a web app that does the accounting for a rotating savings and credit association (ROSCA) like money sharing group. The purpose of this document is to describe how this money sharing group will operate, and to describe how the app will facilitate the accounting side of the group's operation.

### Money Share Description

A money share organization is means by which people can get community funded, 0% interest loans on a rotating basis. We expect that around 60 people will participate in this money share group. The group operates on a fixed time period, generally between a week and two months. At some point during the period, members will give the group organizer some agreed upon amount of money. At the end of the period, the organizer will distribute all of the accumulated money to either one member or a subset of the members. For the next time period, these members will go to the back of the queue. By the time they are next in line to receive money, they will have paid back exactly as much money as they received when it was their turn. Thus, at the end of a full rotation, neither the group nor individual members earn or lose money. In traditional ROSCA schemes, members pay every period of the rotation, but this is not necessary. Here's an example to illustrate how the money share rotation works:

- At the start of the rotation, members agree on the time period and the amount of money they will pay for each time period. In this case, they decide they will pay $100 a piece every month. As there are 60 members, the group decides that the accumulated money will be split between 5 members. Members also decide that for the month after a member receives payment, they will not have to contribute to the pot; in other words, groups at the back of the queue don't pay in. Members are split up into 12 groups of 5.
- At the end of the first month, members from groups 1 to 11 have all contributed $100, meaning that the organizer is holding on to $5500. Each person in group 1 receives $1100. Group 12 did not contribute, as they were at the back of the queue. Group 1 moves to the back of the queue.
- At the end of the second month, members from group 2-12 have all contributed $100. Each person in group 2 receives $1100 dollars. Group 1 did not contribute, and now group 2 moves to the back of the queue.
- This continues for the next ten months. At the end of the rotation, each member has contributed $1100, and they have also received $1100 at one point during the month.

A few questions:

- How do we want to deal with a group with uneven numbers? The above example breaks down if the money share has 59 people. I can imagine a few different ways of dealing with it:
  - We create one group of four members. When their turn is up, each member would receive $1375, but they would compensate by paying $125 a month instead of $100
  - Instead of having a single money share, we actually split the group up into 5 smaller ones, 4 with 12 members and 1 with 11 members.
- Does the money share 
- What do we do if one month someone doesn't pay?
