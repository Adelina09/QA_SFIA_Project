# README
---
# Hot Sauce Recipe Database
---
Written in reference to QAC - Fundamental Project Specification (DevOps Core) - revised edition. This project is for the purpose of fulfilling the specification definition for the project assignment due Week 5 of the DevOps February 17 intake cohort.

## Table of Contents

1. Project Brief
    + Proposal
2. [Trello Board](https://github.com/THC-QA/QA_SFIA_Project/blob/developer/README##Trello_Board)
    + Start Point
    + Rolling Changes
    + End Point
3. Risk Assessment
4. Project Architecture
    + Entity Relationship Diagram
    + Architecture Diagram
    + Issues Encountered
5. Design Considerations
    + Front End
    + Back End
    + UI
6. Testing
    + Pytest Testing
    + Postman Testing
    + Final Report
7. Deployment
    + Toolset
    + CI Server Implementation
    + Branch and Merge Log
8. Front End Implementation
9. Improvements for Future Versions
+ Authors
+ Acknowledgements

## Project Brief
---

### Proposal

## Trello Board
---

I used a kanban board on Trello to manage my workflow during the project, the board was set to public to enable overview and broadcast. Agile methodology was implemented in line with the brief, in terms of product and sprint backlog, although due to the individual nature of the project, no scrum working practices were implemented. The board was set up with reference to potential user stories emphasising the CRUD functionality of the database system. Although unrequired, a Task Backlog was instituted in order to keep the requirements of the project spec clear, so as to enable sprint tasks to be dynamically allocated to them.

Due to this setup sprints could be passed through development, and, if required, testing, before being assigned to Done. Once sprints generated by a backlogged Task have been completed, the task itself can be marked Done. Errors, mistakes, and software bugs are given over to the newly added Bugs column, to be fed back to development and testing when identified and processed.

### Start Point

![A picture of the trello board, started on the first week. The Product Backlog, The Sprint Backlog, the Tasks for the first week have been added. Only the 'Start the Trello board' task has been completed](https://i.imgur.com/op4ChN4.png)

At the start of the project, I focussed on the four tasks most easily completable in the first week of training: Starting the Kanban board [itself](https://trello.com/b/8xaM1s0K/qa-week-5-individual-project-hotsaucerecipe), starting this documentation to streamline my future workflow, instituting a github repository for the project, which can be found [here](https://github.com/THC-QA/QA_SFIA_Project), and initialising the risk assessment for the project in line with my initial understanding.

### Rolling Changes

+ The first major change to the Kanban board was a respec to denote the removing of Selenium testing from the project, due to the lack of javascript implementation. In replacement, a provisional addition of Postman testing was added, so as to validate the REST API, and therefore CRUD functionality of our APIs. In addition, issues with reimaging hardware lead to the need to implement Visual Code Studio usage. To this end I installed the Remote SSH, mySQL, Python, and Code Spellchecker extensions, so as to improve project flow. Notepad++ is being explored in replacement of VIM for GitBASH. The database has been implemented as a simple relationship between two main tables, the user table has been omitted until hashing of passwords and pre-encryption can be handled on the app side.

+ 

### End Point

## Risk Assessment
---

|Risk No.|Risk|Description|Hazard|Likelihood|Impact|Solution|
|---|---|---|---|---|---|---|
|1.1.1|Overrunning on GCP free data limits.|An instance is left running, or an account breach enables the resources on the account to be drained.|Worst case scenario, databases are unaccessable.|1|5|Continue monitoring GCP usage. Copy databases offline as final backup.|
|1.1.2.1|Database security: SQL|The GCP server is breached in some way, compromising data integrity.|Worst case scenario, data is lost, or user data is compromised.|3|5|Ensure user and personal data is encrypted, and passwords hashed, before being moved to the database.|
|1.1.2.2|Database security: SSH|Unmanaged connections cause data leak or damage, keys are lost or stolen.| Worst case scenario, GDPR noncompliance or total data compromisation.|2|5|Learn and make use of GCP's SSH key management role system, and implement it correctly.|

## Project Architecture
---

### Entity Relationships

### Overall Architecture

### Issues Encountered
