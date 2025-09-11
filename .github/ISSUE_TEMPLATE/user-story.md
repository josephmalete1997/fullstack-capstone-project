---
**As a** registered user  
**I need** to search for gifts by category  
**So that** I can quickly find items that match my needs  

### Details and Assumptions
* Categories include "toys", "books", "clothes"  
* Search should be case-insensitive  

### Acceptance Criteria
```gherkin
Given I am on the gift search page  
When I search for "toys"  
Then I see a list of gifts categorized as "toys"  
