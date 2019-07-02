## Backlog Refinement

### Refinement Theory (https://www.scrumguides.org/scrum-guide.html)



> Product Backlog refinement is the act of adding detail, estimates, and order to items in the Product Backlog. This is an ongoing process in which the Product Owner and the Development Team collaborate on the details of Product Backlog items. During Product Backlog refinement, items are reviewed and revised. The Scrum Team decides how and when refinement is done. Refinement usually consumes no more than 10% of the capacity of the Development Team. However, Product Backlog items can be updated at any time by the Product Owner or at the Product Owner’s discretion.

> Higher ordered Product Backlog items are usually clearer and more detailed than lower ordered ones. More precise estimates are made based on the greater clarity and increased detail; the lower the order, the less detail. Product Backlog items that will occupy the Development Team for the upcoming Sprint are refined so that any one item can reasonably be "Done" within the Sprint time-box. Product Backlog items that can be "Done" by the Development Team within one Sprint are deemed "Ready" for selection in a Sprint Planning. Product Backlog items usually acquire this degree of transparency through the above described refining activities.

>The Development Team is responsible for all estimates. The Product Owner may influence the Development Team by helping it understand and select trade-offs, but the people who will perform the work make the final estimate.

Things that are higher/top of backlog or about to happen usually have more details than lower backlog items. It's critical that any items that are selected for Sprint meet the definition of ready and done. Development is responsible for providing estimates. The product owner is NOT ALLOWED to influence the team to make smaller estimates to get more work done. PO should respect the provided estimates. PO cam split the story to help estimates but nothing more in regards to estimates.



### 1. Details

* It's all about collaboration!
 - Detail necessity is dictated with conversations with Development team
 - Some teams need only a few sentences. Other folks need more to best approach problem
 - As time elapses PO's learn their teams temperament and can assess the level of detail needed
 - The perfect amount of detail is whatever lead to the creation of the most software
 - Try face to face conversation first.


* Definition of Ready
  - The Definition of Ready (DoR) defines what PBIs (product backlog items) can go into a sprint. This may be a good option to use but is optional and up to PO's discretion
    - Example:
        - The story has been estimated
        - The story is small enough to fit into a Sprint
        - The story has acceptance Criteria
        - The user interface design is complete
  - Start by asking "What are we doing today ?" and evolve from there.     
  - "What do you guys [Development] need for a PBI to be ready to start developing against it "
    - This is not an argument or a contract; This is a conversation to increase efficiency. Do not state a story is ready and Dev team is not--Be transparent and enable collaboration.

* Acceptance Criteria
 - How much detail is required in the Acceptance Criteria ?
   - Depends on context
      - Let's compare these two proposed acceptance criteria:
        - Option 1: The checkout system will accept all forms of payment
        - Option 2: The checkout system will accept Amex or Visa
      - Both of these are valid under different scenarios. You will need to assess the goal to determine the level of acceptance criteria needed.
 - What format is best ? How will PO and Dev agree/determine which acceptance criteria have been met?
    - A conversation is needed here as well until familiarity is established.

* Design
 - Does UI need to be done before sprint starts ?
  - No right answer it will all be dependent on the project, company and team. Some companies have separate design teams that are independent of development. Otherwise it may in fact be beneficial to finish all UI upfront. In other organizations, PO does a high level sketch and the details are worked out during sprint. This last concept seems to be similar to Mike Cohn's thoughts on creating user story maps.

* Business logic
 - How much do we need to specify ?
  - We should first ask who is responsible for business logic. Sometimes technical architecture and business logic are closely related .Other times not. You can then progress to how much of this is another conversation to flesh out information and how much need to be written. Then we can assess the specificity needed. We are approaching the business logic in the same way we approach Acceptance Criteria.


* FitNesse tests

 - We can allow methods of Acceptance Testing dictate our details and acceptance criteria.

 - One testing method is FitNesse.

> Fitnesse is a automation framework that supports BDD. It was created by Uncle Bob in 2002. FitNesse is a wiki web server, it has a very low entry and learning curve, which makes it an excellent tool to collaborate with, for example, business stakeholders. The wiki pages created in FitNesse are run as tests. The specifications can be tested against the application itself, resulting in a roundtrip between specifications and implementation. - Taken from http://fitnesse.org/

 - Example: Suppose we are developing a multiplication calculator application
 - As PO we can construct tests the software would need pass using Fitnesse; This would provide the perfect amount of detail for Dev and/or QA team.
 - Below is a proposed test we would need to run to confirm our calculator app us working

 | Input  | Input  | Output   |
 |---|---|---|
 |2   |5 |10   |
 |-1  |6 |-6   |
 |0   |2321223 |0   |


### 2. Estimates
* Estimate only when it matters
 - Is the estimate providing value ?
 - Suggestion: Time box all estimates; pick a number and proceed
 - Do not get stuck on estimation; it will suck time
 - Estimates are used communicate and coordinate efforts; not meant to be used for punishment
 - High level teams do not estimate at allow
 - Accuracy vs. Precision:
     > Accuracy: The degree of closeness of measurements of a quantity to that quantity's actual (true) value
      > Example: If we say an item will take 3 days and it took 3 days.

     > Precision: The degree to which repeated measurements under unchanged conditions show the same results
      > Example: If we say it takes 3 story and we do it 10 times how often do we hit 3 days.


  - Effective measurement systems are both accurate and precise
  - Accurate estimates are useful even if the precision is less than PO would like
    - e.g 5 story points plus or minus 3
  - We do not need to estimate a multi-month epic down to a day or a sprint

* Story points

##### What Are Story Points ?
  - Story points are a unit of measure for expressing an estimate of the overall effort that will be required to fully implement a product backlog item or any other piece of work.

  - When we estimate with story points, we assign a point value to each item. The raw values we assign are unimportant. What matters are the relative values. A story that is assigned a 2 should be twice as much as a story that is assigned a 1. It should also be two-thirds of a story that is estimated as 3 story points.

  - Instead of assigning 1, 2 and 3, that team could instead have assigned 100, 200 and 300. Or 1 million, 2 million and 3 million. It is the ratios that matter, not the actual numbers.

##### What Goes Into a Story Point?

Because story points represent the effort to develop a story, a team’s estimate must include everything that can affect the effort. That could include:

The amount of work to do
The complexity of the work
Any risk or uncertainty in doing the work
When estimating with story points, be sure to consider each of these factors. Let’s see how each impacts the effort estimate given by story points:

##### The Amount of Work to Do ?

Certainly, if there is more to do of something, the estimate of effort should be larger. Consider the case of developing two web pages. The first page has only one field and a label asking to enter a name. The second page has 100 fields to also simply be filled with a bit of text.

The second page is no more complex. There are no interactions among the fields and each is nothing more than a bit of text. There’s no additional risk on the second page. The only difference between these two pages is that there is more to do on the second page.

The second page should be given more story points. It probably doesn’t get 100 times more points even though there are 100 times as many fields. There are, after all, economies of scale and maybe making the second page is only 2 or 3 or 10 times as much effort as the first page.
##### Risk and Uncertainty ?

The amount of risk and uncertainty in a product backlog item should affect the story point estimate given to the item.

If a team is asked to estimate a product backlog item and the stakeholder asking for it is unclear about what will be needed, that uncertainty should be reflected in the estimate.

If implementing a feature involves changing a particular piece of old, brittle code that has no automated tests in place, that risk should be reflected in the estimate.

##### Complexity ?

Complexity should also be considered when providing a story point estimate. Think back to the earlier example of developing a web page with 100 trivial text fields with no interactions between them.

Now think about another web page also with 100 fields. But some are date fields with calendar widgets that pop up. Some are formatted text fields like phone numbers or Social Security numbers. Other fields do checksum validations as with credit card numbers.

This screen also requires interactions between fields. If the user enters a Visa card, a three-digit CVV field is shown. But if the user enters an American Express card, a four-digit CVV field is shown.

Even though there are still 100 fields on this screen, these fields are harder to implement. They’re more complex. They’ll take more time. There’s more chance the developer makes a mistake and has to back up and correct it.

This additional complexity should be reflected in the estimate provided.

##### Consider All Factors: Amount of Work, Risk and Uncertainty, and Complexity ?

It may seem impossible to combine three factors into one number and provide that as an estimate. It’s possible, though, because effort is the unifying factor. Estimators consider how much effort will be required to do the amount of work described by a product backlog item.

Depending on how an uncertainty is resolved or a hit risks a PBI may take more time to complete. That mean a risk that is likely to occur and will estimated more than one that is neither likely or time consuming to address.


Estimators then consider how much effort to include for dealing with the risk and uncertainty inherent in the product backlog item. Usually this is done by considering the risk of a problem occurring and the impact if the risk does occur. So, for example, more will be included in the estimate for a time-consuming risk that is likely to occur than for a minor and unlikely risk.

Estimators also consider the complexity of the work to be done. Work that is complex will require more thinking, may require more trial-and-error experimentation, perhaps more back-and-forth with a customer, may take longer to validate and may need more time to correct mistakes.

All three factors must be combined.

##### Consider Everything in the Definition of Done ?
A story point estimate must include everything involved in getting a product backlog item all the way to done. If a team’s definition of done includes creating automated tests to validate the story (and that would be a good idea), the effort to create those tests should be included in the story point estimate.

Story points can be a hard concept to grasp. But the effort to fully understand that points represent effort as impacted by the amount of work, the complexity of the work and any risk or uncertainty in the work will be worth it.

##### Additional considerations
 * They may expressed using Fibonacci sequence: 1,2,3,5,8,13.... 
 * Standard format is to
    * Present a user Story
    * Each member of the Development team applies a value
    * The high and low estimates have a discussion
    * Repeat until everyone agrees on the story point size 
    * Time box and don't get stuck in arguments
    * Review in retro 
  * Suggestion: Try planningpoker.com for distributed teams

  ##### Story Point Pitfalls
   * Amount of time it can cause talking back and forth for appropriate weight
   * Ron Jeffries, who may have invents story point, apologizes for it's creation
   * Do not take into account wait time between teams
   
### Suggested method: Empirical estimation

* Estimate based on the actual performance of the teams
* Record how much time (in days, typically) it takes to complete a Story
* Use a Monte Carlo tool to estimate the completion date 
  - Enter start and finish date for a story 
  - No guessing required
  - About a dozen are needed to create a reliable forecast
  - Check out Troy Magennis Monte Carlo tool at http://focusedobjective.com/free-tools-resources/

### 3. Order

* Dependencies
  - The goal is to have independent user stories.... but that does not always happen
  - As a product owner you should respect technical and product dependencies and use them to order the backlog. 
  - Ask yourself how you visualize dependencies to assess best method to address 
  
* Business Value
  - Most common way to implement ordering is to use business values. You can make several types of assessments to order by business value.
    - Qualitative assessment: Use a rough ordering such as High value, Medium value, Low value.
    - Return on Investment calculation: Value/construct
    - Net Present Value calculation: Discounted Value/Cost
    - Quantifying business value is inaccurate and imprecise. The goal is to do an experiment as quickly as possible. See previous notes
    - Check out https://www.scrumalliance.org/community/article/2014/december/order-your-product-backlog
    
* MoSCoW
 - Must have
 - Should have 
 - Could have 
 - Wont have 

 MoSCoW Example
Take a human body as an hypothetic example:

Must– a heart is “must”. Without it, there is no live organism. What is must in your application?
Should– a hand is “should”. Without it is hard. But you can survive even without hand. Well, in most cases.
Could– hair is “could”. It is fine to have them, you even look nicer, but you will definitely survive without them
Won’t – unnecessary waste. Btw, is there anything “won’t” in a body? (Probably, it might be your appendix?)

### Suggested method: Cost of Delay

Introduced by Don Reinersen and David Anderson 

> Is a month of delay worth a million dollars or a thousand dollars? 

4 types of CoD categories for PBI:
 - 1. Expedite
    - If a bug occurs and causes complete work stoppage. Every minute impact increases an money is lost
 - 2. Fixed date  
    - Government passes new regulation with deadline. If fixed ahead of time there is not alot of value. But if fixed after that deadline then it has high cost of delay.
 - 3. Standard
    - Initially there is a value but then the value begin to flatten out
 - 4. Intangible
    - Technical debt: Removing has a little bit of value; in the future if too high it holds back development 
