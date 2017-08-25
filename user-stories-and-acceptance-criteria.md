# User stories and acceptance criteria

This quickly defines user stories and acceptance criteria.

## User stories

... to be added.

## Acceptance criteria

The acceptance criteria are written in simple language that the customer
would use, just like user stories.

To make sure that the acceptance criteria are good and phrased in a way that
testers can derive acceptance tests from them it is very important
that test / QA is involved in the creation of acceptance criteria.

### Good acceptance criteria

*   State an intent not a solution (e.g. “The user can choose an account” rather than “The user can select the account from a drop-down”)
*   Are independent of implementation (ideally the phrasing would be the same regardless whether this feature/story would be implemented on e.g. web, mobile or a voice activated system)
*   Are relatively high level (not every detail needs to be in writing)
*   Define the boundaries for a user story/feature
*   Clear enough that each can be evaluated to "yes" or "no"
*   Help the product owner answer what they need for this feature to give value
*   Help the team gain a shared understanding of the story/feature
*   Help developers and testers; should be testable
*   Help developers know when to stop adding  more functionality to a story
*   Help to removing ambiguity from requirements

> Note: “I”-format can be used for acceptance criteria to keep focus on the user
> perspective rather than system centric view

### Example - Banking customer and balance

```user_story#
As an internet banking customer
I want to see a rolling balance for my everyday accounts
so that I know the balance of my account after each transaction is applied.
```

Acceptance criteria:

*   The rolling balance is displayed
*   The rolling balance is calculated for each transaction
*   The balance is displayed for every transaction for the full period of time
*   The balance is not displayed if a filter has been applied

### Example - Snapper card holder

```user_story#
As a Snapper cardholder
I want to be able to pick up my pending credit from MySnapper (Note: MySnapper is a client applications for users to top up their ePurse, check their balance etc)
so that I have money on my ePurse
```

Acceptance criteria, using I-term:

*   I can see on MySnapper that there are pending credit(s) for my card
*   I can choose which credit(s) to pick up
*   I can see my new purse balance when I have chosen to pick up a credit
*   I can’t top up my card or buy a pass when there are pending credits for my card

### Definition of done

"Done" is repeatable.

*   Acceptance criteria met
*   Code is reviewed by another development team member
*   Test cases are written
*   Unit tests and UI automation tasks are written
*   Feature is tested for accessibility
*   Feature is tagged for analytics

### Resources

*   [Nomad8 - Acceptance criteria](http://nomad8.com/acceptance_criteria)
*   [BoostAgile - Acceptance criteria and user stories](http://www.boostagile.com/user-stories-part-2-acceptance-criteria/)
*   [Definition of done](http://blog.teamtreehouse.com/when-is-a-user-story-done-acceptance-criteria-definition-done)
