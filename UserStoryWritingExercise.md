
## Create bank ATM backlog



### Identify Personas:
* 29 – Male – IT – Median Income—Parent on the go
* 29 – Female—Spouse—Parent on the go

### User Stories and Acceptance Criteria: 

1.	As a bank customer I want to use my debit card to withdraw money
 * System correctly interprets debit card magnet stripe
 * System rejects incorrectly formatted or other cards (other bank, credit card, library card)
 * System displays an error message when it rejects a card
 * System executes money dispense command from machine to physical withdrawal area
2.	As a bank customer I want to withdraw from my checking account
 * System accesses only checking account
 * System alerts customer transactions will only occur on checking account
3.	Given that a spouse has authorization to withdraw from joint account when a spouse uses their debit card then they should have ability to withdraw money
 * System correctly alternative card as provided by bank for account access
 * System rejects incorrectly formatted or other cards (other bank, credit card, library card)
 * System displays an error message when it rejects a card
4.	In order to understand options I want to see my starting balance
 * After login system will display total prior to any transaction
5.	As a bank customer I want to secure my transaction with a numeric pin code
 * System accepts correct 4 digit pin
 * System rejects incorrect 4 digit pin
 * System displays confirmation of correct pin
 * System displays rejection notification of incorrect pin


6.	Given that a withdrawal was made and account balance has changed then I should have a display of the new total
 * System subtracts withdrawal amount from beginning total
 * System displays new total
7.	Given that a withdrawal was made when transaction is complete then the customer should receive a hard copy receipt
 * When system recognizes withdrawal it will ask customer if transaction is complete
 * System will allow user to reply with yes or no
 * If yes, system will execute print receipt command 
 * If no, program will allow for more withdrawals
8.	As a user I want to be prompted for paper or email receipt so that we can be environmentally conscious 
 * When system recognizes withdrawal it will ask customer if transaction is complete
 * System will allow user to reply with yes or no
 * System will then ask if email or print is desired
 * If email, system will request email address
 * If yes, system will execute print receipt command 
 
9.	In order to feel secure  I want to swipe my debit card through machine so that I retain my physical card (card not inside machine)
 * System will use magstripe swipe technology
 * System will tell customer to swipe and remove card quickly
 * System will confirm swipe was effective
 * If swipe was too fast system will display message
 * If swipe fails system will display message

10.	As a bank customer I want to select amount to be withdrawn from balance
 * SPIKE: Take one day to research most frequently used denominations
 * System will display 6 denominations in intervals based on spike results
 * 	When selected interval denomination will be subtracted from balance
