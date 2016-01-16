# Commitment Notes

My notes from a novel about managing project risk.

http://commitment-thebook.com/

## Types of Options

### Financial options

* Read more about tulip contract trading as windhandel.

  https://en.wikipedia.org/wiki/Tulip_mania

* Two parties entering into the option:

  * the buyer of the option (She pays a premium for the option. Expiry of the option is specified in the options contract.)
  * the seller of the option who takes on a commitment

### Embedded options

It's an option that occurs in a legal contract, which was not specifically intended to be an option. The buyer and the seller might be unaware about it.

Example:

* Operational Tolerance in Oil Contracts

  Contract for 100 000 barrels with 5% tolerance which means the contract is for 95 000 barrels plus an option to buy a 10 000 barrels.

  When price of the oil has gone up then the buyer can buy extra 10 000 barrels cheaper.

  When the price of the oil has gone down then the buyer can takes only minium 95 000 barrels.

* Phased contracts

  For instance IT contracts with specified price for phase 2. The buyer can decide if he wants to start second phase with set price depends how the first phase went. He can also choose another supplier for second phase if he thinks he can get it cheaper.

### Real options

* Options have value

  * value of the benefit received (intrinsic value)
  * being able to choose later is valueable (it's more valueable when there is more uncertainty)

* Options expire

  * Keep track under what condition and option is no longer available.

* Never commit early unless you know why

  * Commitment is when you decided to do something.
  * Making commitment destroys options to realize some value.
  * It's important to understand why you destroy one thing to create another.
  * It's not about committing as late as possible (this might expose to higher and unnecessary risks). It's about gathering information and trying to push the expiry date later so you can make decision with more data.
  * Manage an options that are most important to you.

Example of real options:

* buying a flat
* phoning a friend
* finding a new job
* travelling somewhere

## Relationships and knowledge options

* Relationships are one of the most valueable options

* Knowledge options

  * Learn about a subject to understand:

    * what can be done with the tools
    * how long it will take to learn the tools so you can apply them
    * find a mentor for a subject

  | 2. conscious incompetence   | 3. conscious competence   |
  |-----------------------------|---------------------------|
  | 1. unconscious incompetence | 4. unconscious competence |

  * Be (2) consciously incompetence about a subject:

    * you should know how long it takes to become (3) consciously competence

      * if it takes long time to learn and subject is useful then learn it early
      * if it takes short time to learn the subject then learning commitment can be later.

## 3 things you need to know on your project

### Where you are going

  * Use real options to handle uncertainty
  * Avoid committing too early

3 approaches:

* postpone the commitment and collect more information
* choose the option that is easiest to change
* invest in a different approach that allows change to be easier
  * For instance use repository pattern which delayes the commitment what data store you will use

### Where you are

  * Task statuses:

    * not started
    * work in progress
    * done

  * It's more important the team knows the status of the project than the management

  * Team can co-ordinate their activity

### How to get between the two as quickly as possible

  * Focus on time rather than cost
  * Leave developers and testers with their tasks
  * Focus on blocked items.
  * Focus on queues or waiting states.
  * Ensure people are working on one item at a time
    * People working on multile tasks means you have hidden queues
    * Task switching is ineffective - it's signal that things are blocked but not reported
  * Technical debt can speed up development (more about paying it later)
  * One of the most important things is to identify dependencies on the project
    * Find a way to break dependencies between tasks

## Visualisation Boards

https://en.wikipedia.org/wiki/Kanban

https://en.wikipedia.org/wiki/Lean_software_development

    https://en.wikipedia.org/wiki/Kanban_(development)

## Feature Injection

Move toward the outcome until you encounter value.

* Hunt the value
* Inject the feature
* Break the model

### Ways of generating value:

* increasing revenue
* protecting revenue
* reducing costs
* avoiding costs

### Options to generate revenue

* Network
  * social networks are more valueable if they have more users or a bigger network
  * telephones

* Usage
  * more users use the service then more likely they will generate revenue

* Value in numbers
  * graph of the trend

Think about context and where the value could be. Where the value is coming from?

## Staff liquidity

* value in shorter iterations of development
  * short iterations provide more options which means more ways to control the project and manage the risks

* Low liquidity means it's hard to move staff around on projects

* High liquidity means it's easy to to scale project up and down and do it quickly

* Staff liquidity is the time needed to:
  * Approve and hire people
  * Gel the team
  * Train the team

### How to achieve high staff liquidity

* No key man dependencies on a project
  * be aware about key man dependencies
  * https://en.wikipedia.org/wiki/Bus_factor
  * ensure the organisation has more than one or two people who can perform each function within the organisation or group
  * grades people for each function
    * levels:
      * 1 - can perform basic of the function
      * 2 - can perform the function adequately
      * 3 - the function has no secrets to them
    * function with 3 or more people at level 3 is safe (Green)
    * function with 2 people at level 3 is at risk (Yellow)
    * function with 1 or no people at level 3 is risk (Red)
  * functions that take longer to train are riskier than those that can be taught quickly
  * assess the risk on a regular basis and track the changes

* Allocate people with the fewest options first, people with most options last

* Let people with most options coach and help the people with the least options

## Game Theory

https://en.wikipedia.org/wiki/Game_theory

* Prisoner's Dilemma

  https://en.wikipedia.org/wiki/Prisoner%27s_dilemma

* Strategy of Conflict

  https://en.wikipedia.org/wiki/Thomas_Schelling

  "[Y]ou're standing at the edge of a cliff, chained by the ankle to someone else. You'll be released, and one of you will get a large prize, as soon as the other gives in. How do you persuade the other guy to give in, when the only method at your disposal – threatening to push him off the cliff – would doom you both? Answer: You start dancing, closer and closer to the edge. That way, you don't have to convince him that you would do something totally irrational: plunge him and yourself off the cliff. You just have to convince him that you are prepared to take a higher risk than he is of accidentally falling off the cliff. If you can do that, you win."

### Group's dynamics in the context of Game Theory

* Each member withholds information and tries to win. They adopt the Strategy of Conflict.
  * conflict stats occur as members in the group start to fail.
  * Eventually a member fails which causes the group to fail.
  * After the group failure, members start to share information with each other.
  * Eventually the group becomes effective because each memeber has information needed to make the best decision.

To summarize, group goes through the stages:

* forming
* storming
* (failure)
* norming
* performing

See Tuckman's stages of group development:

https://en.wikipedia.org/wiki/Tuckman%27s_stages_of_group_development

### Real Options

People preferences in this order:

* Being right
* Being wrong
* Being uncertain

What does it means?

* It means if you can insert enough uncertainty then the group will perceive the situation as failing and tip into collaboration.

* If there is too much uncertainty for a sustained period then the group which is collaborating will tip into conflict.

  * Managers engaging in reorganisation may be advised
  * Slowly reorganisation is more damaging than the one done quickly

* Important lesson: anyone who suppresses conflict prevents healthy group development.
  * Accelerating conflict and making it earlier means the group progresses earlier and engages in smaller conflicts than the big conflict caused by suppressed feelings
  * Team learns conflict resolution skills rather than conflict avoidance

What's the opposite of good relationship?

* It's not a bad relationship, it's __no relationship__.
  * look for people in the team who do not communicate with each other
  * non-communication is often the result of conflict avoidance
    * it's covert conflict with the health of the group

### People hate uncertainty

* Real options is a rational decision process
* Most people are not rational
* People hate uncertainty so much that they want to make a decision now even if it risks being wrong
  * Given the choice between wrong or uncertain people will prefer certainty
  * People hate uncertainty more than they dislike being wrong
  * If you inject uncertainty then people feel like it's failed and start to collaborate

Rather than have total uncertainty we have to create bounded or condition uncertainty.

### Choice overload

* Choice overload reduces engagement.
* Too much choice is a bad thing (decision paralysis)
* Paradox of Choice, why less is more

  Schwartz's estimation, choice has made us not freer but more paralyzed, not happier but more dissatisfied.

  https://en.wikipedia.org/wiki/The_Paradox_of_Choice

  http://www.ted.com/talks/barry_schwartz_on_the_paradox_of_choice?language=en

### How to value real options?

https://en.wikipedia.org/wiki/Black%E2%80%93Scholes_model

* Black Scholes model works well in Financial Market.
* In the real world liquidity dominates the quation.
* In context of real options the Black Scholes model is invalid.
  * For instance bottle of water could be worthless or worth a person's life depending on context.

## Scenario planning

Scenario planning is an another expression of real options.

It was popularised by Peter Senge's book:

https://en.wikipedia.org/wiki/The_Fifth_Discipline

### Preparing for the possible

* Scenarios have the effect that the organisation start communicating and collaborating in ways that it had not seen before.

* The creation of risk management scenarios has immediate positive benefits beyond just being better prepared for a possible future.

### Scaling scenario thinking

Scenario Analysis or risk management can be applied at any scale. From individual, up to the corporation and the global scale.

### Increase your odds in the future

Prepare for the multiple possible futures and have your options for each in place.
