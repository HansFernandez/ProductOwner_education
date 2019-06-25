## User Stories

### User Story Theory
 * Written in the language of customer
  - Setup the database would be incorrect
 * Not Required by SCRUM "The guide says "the backlog is composed of PBIs"
 * User stories are a reminder to have a conversation
    - Job is not done because user story is Written
    - Development conversation needs to be had
*   There is no true standard
    - The real goal is to communicate; contexts and culture will define if user stories are appropriate
    - No such thin as a universally good user Story

#### Typical Formats
 * Most common: As a <type of user>, I want <goal> so that <some reason>.
 * Another form:  In order to <receive benefit> as a <role>, I want <goal>
 * Gherkin Format: Given x when [action take] then [result of action]
   * Given that the customer is on the checkout page of the site when the customer enters a valid Amex number
   then the system sends the customer an email confirmation

All user story formats need specify who, what and why. Choose best to communicate with Dev. team

###### Roles and Personas

Sometimes when we start our user story we need to define roles and personas. This will assist in the "As a" clause we see in user story formats.

Roman Pichler provides a great template we can use:

What does the persona look like? What is its name? Choose a picture and a name that are appropriate and that help you develop sympathy for the persona.

What are the persona’s relevant characteristics and behaviors? For instance, demographics such as age, gender, occupation, and income; psychographics including lifestyle, social class, and personality; behavioral attributes like usage patterns, attitudes, and brand loyalty. Only list relevant details.

Why would the persona want to use or buy the product? What benefit does the persona want to achieve? Which problem does
the persona want to solve?



#### Acceptance Criteria

* Defines, from the customer's perspective, when a user story is done.

Example: As an ecommerce customer I want to pay with Amex so I can earn miles.

Criteria:
  System accepts correctly formatted Amex #'s
  System rejects incorrectly formatted Amex numbers
  System displays an error message when it rejects a numbers


### INVEST Criteria

If the story fails to meet one of these criteria, the team may want to reword it, or even consider a rewrite (which often translates into physically tearing up the old story card and writing a new one).

A good user story should be:
```
"I" ndependent (of all others)
"N" egotiable (not a specific contract for features)
"V" aluable (for customer perspective)
"E" stimable (enough details present to approximate if it can be completed in sprint)
"S" mall (so as to fit within an iteration)
"T" estable (in principle, even if there isn't a test for it yet)
```

### DEEP Product Backlog
```
"D" etailed Appropriately.
    User stories on the product backlog that will be done soon need to be sufficiently well understood that they can be completed in the coming sprint. Stories that will not be developed for awhile should be described with less detail.
"E"stimated.
    The product backlog is more than a list of all work to be done; it is also a useful planning tool. Because items further down the backlog are not as well understood (yet), the estimates associated with them will be less precise than estimates given items at the top.
"E"mergent.
    A product backlog is not fixed. It will change over time. As more is learned, user stories on the product backlog will be added, removed, or reprioritized.
"P"rioritized.
    The product backlog should be sorted with the most valuable items at the top and the least valuable at the bottom. By always working in priority order, the team is able to maximize the value of the product or system being developed.
```

### Splitting Stories

* Stories are split when too large for one sprint
* When splitting we need to keep customer focus
* Anti-Pattern alert: Do not split stories based on technical aspects.
  * A UI, a UX, a Database split does not deliver valuable

[Embed Horizontal vs. Vertical Split]

#### Splitting Stories Approaches

1. Workflow Steps
2. Business Rule Variations
3. Major Effort
3. Simple to Complex
4. Variations in Data
5. Data Entry Methods
6. Valid vs. Invalid
7. Defer Performance
8. Operations (e.g. CRUD)

### Spikes!

* a SPIKE is a time-boxed research task for a specific outcome
  * Spend 2 days to assess which tools allows for better data retrieval
* They can be separate PBI or within a user story
* PO decides how much time to spend and maximize valuable
* Anti-Pattern Alert: Not every User Story needs a spike!
