**As a** customer service representative  
**I need** to read customer account information  
**So that** I can view their details quickly when they call support  

### Details and Assumptions
* Account information includes name, address, and contact details.
* The customer should be authenticated to access their own account.
* Only authorized personnel can access account details of other customers.

### Acceptance Criteria  
gherkin
Given the customer is logged in and authorized  
When they request their account information  
Then the system retrieves and displays the account details
