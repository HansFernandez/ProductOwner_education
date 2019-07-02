# Write Better User Stories in Less time with Less Aggravation
## The 3 surprising techniques of Top Agile Teams

How to stop day-to-day emergencies (and yelling stakeholders) derailing your progress in an iteration.
Why you need 1 to 2 clearly defined goals quarterly and how to decide what they should be
A step-by-step way to plot user stories so you can prioritize faster and clearly communicate to stakeholders what you will build
3 Factors that tell you if the story you're splitting is potentially shippable. Hint: It can be 100% worthless to the end user but still make stakeholders happy.
Too much detail is worse than too little


Product Backlog was seen as junk drawer in the past. No refinement or user stories were written.

User Stories Origin = Kent Beck Extreme Programming Explained


## 3 Fundamentals

## 1. Conduct Quarterly Story-writing workshop
  * This will not slow down
  * Allows you to focus on the bigger picture
  * Pick a goal or two for the coming quarter
  * Write stories to achieve the goal(s)
  * Run iterations
  * Stories will continue to appear under normal operations; this proposal does NOT mean to stop user story creation at other times. The goal of the workshop is to have a deliberate, focused meeting where brainstorming of the quarter's most important goal occurs.
  * There is always a fire to put out. When teams reflect back on past iterations they usually discover they did not get much done (from PBI perspective) because of the iterative and incremental nature. Every sprint look at what to work on and emergencies/fires always rise to the top.
  * Important > Urgent
  * An overly short planning horizon; PO chooses most important thing to work on but sometimes most important thing is NOT what stakeholders are yelling about. When team writes user stories each iteration causes team to address urgent rather than important.
  * Short-term focus leads to problems
    - Team doesn't deliver maximum value
    - Stakeholder become dissatisfied
    - Team members become frustrated by changes
    - Business doubts the benefits of Agile
 * Without larger goal every crisis seems worth addressing; can be used as an anchor point to compare crisis against. The larger goal needs to be met and should bring perspective to crisis.

 * Success tips for quarterly Story-writing workshop
    - Focus on a single significant objective
    - PO selects objective by working with stakeholders; a good one is big enough it will take about 3 months to complete
    - User Stories are then fleshed out and sprints are formulated to chase the goals

                                                  ###### MVP vs MMF
 * MVP -- A version that gets the max amount of information with the least effort. MVP and then Ultimate Product. (Source Erik Reese "The Lean Startup")
 * Unfortunately, it's truest definition can only be used once. Often teams fall into "What's next" after MVP creation.
 * Mike prefers MMF Minimum Marketable Feature (MMF). MMF is a subset of an overall feature that delivers value when released independently.(Source: Software by Numbers). It is smaller than MVP
 * Wildly Important Goal (WIG) or Big, Hairy, Audacious Goal (BHAG) should be the quarterly objective

Cupcake Analogy:
  MVP is a homemade impromptu frosted cupcake.
  Ultimate product is sleek delicious cupcake with cherry on Top
  MMF would be the presentation of the cake base with no frosting or just frosting as the release.
  a full blown cake would be a WIG or BHAG


  *  Involve the whole team in writing stories
 * Involving whole team may seem inefficient
 * When developers are present during user story creation there will be less questions later
    - They may recall how/why user story was written. This will provide context for later recall; they may even come up with better implementation from having heard direct user request
    - More people means more points of view which helps increase creativity

  * Visualize user stories with a story map
 * Invented by Jeff Patton
 * Laid out like grid with rows and columns. We read across but inserting the word then between story cards. Example A then B then C then D. Do not treat literally! It's not meant to be detailed. We read down by mentally inserting the word 'OR'.  These should be sorted with priorities at the top of the column with priority descending downward.
      * Facebook Example: User Login>Post>Check timeline ---- Is this the only way users interact with FB? 
        * Absolutely not users are free to take several paths after login. Some steps will be optional as well.
 * As paths are discovered a row of blue card can be added to the top to represent titles/labels for functionality 
 
## 2. Split stories to demonstrate progress even if the result is not truly shippable

  * Asking for progress is often a loaded question to ask development. As an issue is explored and worked new things creep up. This leads to the running joke "The change is 90% complete." It's not an indication of a lazy development team or slow team it's just the nature of developing software. The agile way to address this is to break user stories down to a very lightweight component than can be chained to other lightweight stories that over time accomplish a feature

  * The art of these breakdown are know an story splitting. Mike Cohn favors a few approaches and recommended the following:
    * Splitting by Interfaces 
      * Assume a CRUD application exists and needs to have both a front end and backend to function.
      * If all the front end is developed with no backend then the site looks great is highly unusable. Very low value to users therefore not a good optional
      * If backend is all built there is nothing to provide to customer at all. 
      * PO should strike a balance by creating specific function targets and developing those small front end and back end aspects first. This will allow for small releases to customer that overtime will improve. At any time it's technically shippable despite how low budget it may appear. It may not be optimal but it is releasable. 
      * Potentially shippable should be:
        * High Quality
        * Tested
        * It does what it was built for very well
        * 
      
    * Splitting by Rules
      * If a particular rule is needed first that is where to focus should be. If any items can be hard-coded to create a schema it can be done so and later sprints can work on replacing the hard-coded value with what is needed.
      
  * This technique will help save time in backlog refinement and iteration planning meetings and bring a focus back to developing for customer value 
    
## 3. Strive to add just enough detail, just in time

  * Too much details too soon
    * Wastes time if feature is dropped or delayed
  * Too little detail too late
    * Slows team while waiting for answers
  * Danger: Team members will want to know all details before starting a Story  
    * Why does this happen?
      * Devs under pressure to deliver perfect estimates
      * Uncomfortable with uncertainty 
      * This causes block like patterns in thinking and puts us back to waterfall style
      * Err on the side of too little, too later
        * In this scenario though bad we can fix team members not knowing how more quickly than the latter. 
  * Two questions for adding details  
    * Do you need the answer before you start on the story ?
      * Sometimes developers request for information and it can lead into a rabbit hole. Let's say a project requires building a button on a website. Suppose developer asks whether a color should be blue or red? Is it really necessary to know this? The focus for the iteration should be to build the button and the color can be arbitrary. Later we can pick a better button color.
    * Did we get answers just in time in just-enough detail ? (During Retro)
  * When you get it right...
    * You'll spend less time in product backlog refinement
    * Team member embrace rather than fear uncertainty
    * You reduce the calendar time needed to deliver a Feature 
      * Which delights customers
  
