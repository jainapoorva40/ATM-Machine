# ATM-Machine

Introduction
This is an example of a Use-Case Model as it would appear in the Inception. Primary actors and
use cases are identified. There may or may not be an outline of the basic flows yet.

Overview
The Automated Teller Machine is a remote unit connected to the bank computer systems. The
purpose of the system is to bring regular bank services closer to the customer and increase the
working hours to around the clock. It is also important to decrease the amount of bank cashiers.
An ATM withdrawal is less expensive for the Bank than a withdrawal from a teller.
The ATM system requires that each bank customer has an ATM card and remembers his PIN
code. The whole security of this system builds on the PIN code.

1.Problem Statement
Automated Teller Machine (ATM) also known as ABM (Automated Banking Machine) is a
banking system. This banking system allows customers or users to have access to financial
transactions. These transactions can be done in public space without any need for a clerk,
cashier, or bank teller.The user is authenticated when enters the plastic ATM card in a Bank
ATM. Then enters the user name and PIN (Personal Identification Number).User checks the bank
balance as well as demands the mini statement about the bank balance if they want. Then the
user withdraws the money as per their need. If they want to deposit some money, they can do
it. After complete action, the user closes the session.If entered account number and PIN is
found to be incorrect, the client has to start the authentication process again.

2. Discussion/Brainstorming
After analyzing the context and comprehending the final user’s problem, it was necessary to
define the exact necessity that would be solved. After that, the group members started the
discussion on all the possible solutions. In the meeting some ideas comes in the picture .

1) Rethinking the challenge
New challenge: Based on the insights
discovered in the last phase of comprehension, and the
constraint mentioned, the team defined the following
specific challenge: “How can we lower the minimum withdrawal amount through the
ATM at each time for the clients.” “How could we give alternative options
to technical change, quickly and safely, to achieve greater
digitalization of our clients and non-clients?”

3) Generating Ideas
The ideation was started with a brainstorm performed
between all the group members. As we set the 500 rupees as the initial minimum
amount for all the clients and every client has to withdraw the amount in multiples of
the same. But it can be infeasible for some of the clients . We decided to lower the
minimum amount boundary upto 100 rupees so that more combinations of notes will be
available for the client.

3 Actors
3.1 Bank Customer
This actor represents a person with a valid Bank Card. The Bank Card is theirs and they know the
PIN Code.
3.2 Bank
This actor represents the financial institution that provides services to the ATM. Responsible for
verifying Bank Customers, authorizing transactions and recording completed transactions.
4 Requirements

4.1 Functional Requirements
● Customers can withdraw the cash.
● Customers can check available balance in the account
● Customer can request for mini statement
● Customers can deposit funds

4.2 NON Functional Requirements
● The PIN must be entered correctly in the first try .
● Users can exit or enter the account after entering the correct account number and PIN.
● Users can only withdraw the amount in the multiple of the currency notes available in
the ATM Machine.
● The ATM is secure so the user can only withdraw a deposit after entering the correct
account number and the PIN.
● A Customer can not withdraw more than Rs 10,000 in one go.
● After the three incorrect trials,the account must be locked.
● In the case of a locked account,only the bank has the authority to unlock it
