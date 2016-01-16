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

