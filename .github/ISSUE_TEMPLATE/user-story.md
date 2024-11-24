---
name: User Story
about: About adding red button
title: ''
labels: ''
assignees: ''

---

**As a** [user] 
 **I need** [red button on the left]  
 **So that** [I can stop the process]  
   
 ### Details and Assumptions
 * [User needs to be able to stop the process that is started]
 *  [User should be warned of consequences if the  process is stopped]
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given [that I started the process]
 When [I push that red button on the left to stop the process]
 Then [the warning message arises]
 and also then [I confirm this action execution again by clicking "YES"]
Then [ the process is stopped] 
But If [ i wish to continue the process after the message pop-up, I click "NO"] 
Then [the process continues  without changes untill next attempt]

 ```
