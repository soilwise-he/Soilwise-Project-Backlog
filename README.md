# Soilwise-Project-Backlog
This README file contains a guideline for using this github soilwise-he repository as a backlog for the Soilwise project
[slides](https://ilvo.sharepoint.com/:p:/s/HESoilWiseProject/ERdMVUvKJaBCjgxdng7UcoYBISZXlAl7E4_2RQnczMzC1Q?e=17lm7D)

work in progress!!

Any questions or comments related to this documentation, please provide as 'issue' and it will be looked at and integrated into documentation


## 4 aspects to be used for backlog
- _Repository_: contains issues, one or more repositories per technical component (pragmatic approach)
- _Issue_ (within repository): use as measurable task/ticket to breakdown requirement, preferably with acceptance criteria
- _Discussion_: more a concept/ an aspect that has to be discussed for future development; when becoming more scoped/tangible, set up new issue and refer to discussion to keep issue (ticket) clean
- _Project_: monitor and plan tasks a development team is working on in view of a technical component

Repositories, discussions and projects can be selected from their specific icons in the top bar of the soilwise-he repository: 
![repositories_etc.png](repositories_etc.png)

Issues are found and grouped within a specific repository, they can be selected from the "issue" icon in the top bar of a repository:
![issues.png](issues.png)

## creating repository
https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository

A new repository can be created by: 
- first selecting the "Repositories" icon in the top bar
- then selecting the green button "New repository" in upper right corner

![create_repo_1.png](create_repo_1.png)

- in the next panel:
  - add a name for the repository related to the technical(sub)component being developed
  - provide a description
  - select public status
  - check box "add a README file"
  - select a license 'e.g. MIT License"'

![create_repo_2.png](create_repo_2.png)


## identifying technical components and GA project-tasks related to repository
Start the README.md document by providing labels for the technical component and tasks related to this document, e.g. INTERLINKER - T2.3 & 3.3 
(other option could be adding tasks in repository name?, immediately visible in the soilwise-he repository).

In addition, in the same README.md document provide information about the technical (sub)component being developed in this repository, e.g. scope, functionality, ...

## creating issue (representing a task or requirement)
https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue

**Keep tasks/issues small**: 
_"High granularity helps to see and feel the progress, not only by the developer but also by the product owner. Smaller tasks are also easier to comprehend, and estimate and result in smaller chunks of code that cover task requirements. Resultant code in turn is often easier to test, refactor, review and integrate."_ 

A new issue for a specific repository can be created by: 
- selecting the "Issues" icon in the upper bar of the specific repository

![create_issue_1.png](create_issue_1.png)

-  selecting the green button "New issue" in upper right corner

![create_issue_2.png](create_issue_2.png)

- in the next panel:
  - add a title
  - add a description for the task that has to be handled/developed  
  - if wanted, on the right select an assignees, add labels ([configure labels for repository](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)) or group in a certain project (project already has to exist) for monitoring and planning the task in the development team
  - when ready select "submit new issue" button in lower right-hand corner

![create_issue_3.png](create_issue_3.png)

## creating discussion

https://docs.github.com/en/discussions/quickstart

(further documentation when we start using it)

## creating project

https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project

A new project can be created by: 
- first selecting the "Projects" icon in the top bar
- then selecting the green button "New project" in upper right corner

![create_project_1.png](create_project_1.png)

You can then start from a template, select "Featured" and e.g. Kanban
Or you can start from scratch

![create_project_2.png](create_project_2.png)

Provide a descriptive name to the project and hit the green button "Create project" in the bottom right corner

![create_project_3.png](create_project_3.png)

The project can then be further configured via selecting settings in the upper left "..." icon

![create_project_4.png](create_project_4.png)

A description can be provided as wel as certain labels ([how to manage labels](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)) to follow up in monitoring, e.g. tasks can be filterd in the kanban board via added labels
Possible custom fields to include in describing issues in the project are
- Status
- Size estimation
- WP

![create_project_5.png](create_project_5.png)

!! Do not use a priority label, the Copmonent or WP leads will rank the tasks/issues from highest priority to lowest priority, the ranking of the tasks/issues represent the priority ranking



## pushing issue to 'Soilwise Project Backlog' and further describing issue
- Status 
- WP
- Startdate
- Enddate


## sprint refinement meetings
Weekly scrum of scrums with component leads and WP leads held on thursday afternoon.
A (cross-component) issue wanting to discuss during weekly sprint refinement meeting has to be mentioned to Nick a day in advance
(how, mail or via Git?)


## components, leads + collaborations
[architectural design with components (D1.3)](https://ilvo.sharepoint.com/:w:/r/sites/HESoilWiseProject/Gedeelde%20documenten/General/Deliverables/WP1-ISRIC/Deliverable%201.3%20Repository%20Architecture/Deliverable%20D1.3%20Repository%20architecture.docx?d=w79c5891907de4ab9bb02c89c4e142560&csf=1&web=1&e=bfKc2i)

**Manual Ingestion**
- lead: WE
- contributors: Paul, MU

**Data export, download**
- lead: WE
- contributors: Paul, MU, CREA

**Hale Studio**
- lead: WE
- contributors: Paul, MU, CREA

**Usage system & Monitoring**
- lead: WE
- contributors: Paul

**SWR Harvester**
- lead: Paul, Cenk
- contributors: Rob & team, Nick

**Ingestion Validation**
- lead: MU
- contributors: Paul, Thorsten, Cenk

**Metadata & Data & Knowledge Validation**
partially a research objective
- lead: Anna + PhD
- contributors: MU, Hugo, WE

**PyCSW**
- lead: Paul
- contributors: MU, Nick

**Map Server**
- lead: Paul
- contributors: MU

**Interlinker**
- lead: Rob & team, Anna
- contributors: Nick

**GIT**
- lead:
- contributors:

**PostgreSQL**
- lead:
- contributors:

**Triple Store**
- lead: Rob & team, Anna
- contributors: Nick



