## 1. Four aspects to be used for backlog
- _Repository_: contains issues, one or more repositories per technical component (pragmatic approach)
- _Issue_ (within repository): use as measurable task/ticket to breakdown requirement, preferably with acceptance criteria
- _Discussion_: more a concept/ an aspect that has to be discussed for future development; when becoming more scoped/tangible, set up new issue and refer to discussion to keep issue (ticket) clean
- _Project_: monitor and plan tasks a development team is working on in view of a technical component

Repositories, discussions and projects can be selected from their specific icons in the top bar of the soilwise-he repository: 
![repositories_etc.png](repositories_etc.png)

Issues are found and grouped within a specific repository, they can be selected from the "issue" icon in the top bar of a repository:
![issues.png](issues.png)  
***
  

<br />
<br />



## 2.1. Creating a new repository
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
***
<br />
<br />
<br />

## 2.2. Identifying technical components and GA project-tasks related to a repository
Start the README.md document by providing labels for the technical component and tasks related to this document, e.g. INTERLINKER - T2.3 & 3.3.<br />
A list of the technical components can be found at the end of this document in section "10. Components, leads + collaborations".
<br />
<br />
(_an other option could be adding GA project-tasks in the repository name?, immediately visible in the soilwise-he repository_).
<br />
<br />
In addition, in the same README.md document provide information about the technical (sub)component being developed in this repository, e.g. scope, functionality, ...
***
<br />
<br />
<br />

## 3. Creating a new issue (representing a task or requirement)
https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue

**Keep tasks/issues small**: 
_"High granularity helps to see and feel the progress, not only by the developer but also by the product owner. Smaller tasks are also easier to comprehend, and estimate and result in smaller chunks of code that cover task requirements. Resultant code in turn is often easier to test, refactor, review and integrate."_ 
<br />
<br />
A new issue for a specific repository can be created by: 
- selecting the "Issues" icon in the upper bar of the specific repository

![create_issue_1.png](create_issue_1.png)

-  selecting the green button "New issue" in upper right corner

![create_issue_2.png](create_issue_2.png)

- in the next panel:
  - add a title
  - add a clear and concise description for the task that has to be handled/developed, consider adding specific aspects about the problem, scope, objective, dependencies, resources
  - > It is important to also add one or more acceptance criteria or a definition of done for each task in the description
  - if wanted, on the right select an assignees, add labels ([configure labels for repository](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)) or group in a certain project (project already has to exist) for monitoring and planning the task in the development team
  - when ready select "submit new issue" button in lower right-hand corner

![create_issue_3.png](create_issue_3.png)
***
<br />
<br />
<br />

## 4. Creating a new discussion

https://docs.github.com/en/discussions/quickstart

TBD
(further documentation when we start using it)

There are multiple categories that can be started as discussion:
![create_discussion_1.png](create_discussion_1.png)

Select for instance "Ideas" and provide a title and content to the discussion you want to start with the community.
When ready, select the green button "Start discussion" in the lower right corner.
![create_discussion_2.png](create_discussion_2.png)

***
<br />
<br />
<br />

## 5 Creating a new project

https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project

A new project can be created by: 
- first selecting the "Projects" icon in the top bar
- then selecting the green button "New project" in upper right corner

![create_project_1.png](create_project_1.png)

You can then start from a template, select "Featured" and e.g. Kanban.
Or you can start from scratch.

![create_project_2.png](create_project_2.png)

Provide a descriptive name to the project and hit the green button "Create project" in the bottom right corner.

![create_project_3.png](create_project_3.png)

The project can then be further configured via selecting settings in the upper left "..." icon.

![create_project_4.png](create_project_4.png)

A description can be provided as wel as certain labels ([how to manage labels](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)) to follow up in monitoring, e.g. tasks can be filterd in the kanban board via added labels
Possible custom fields to include in describing issues in the project are
- Status
- Size estimation
- WP

![create_project_5.png](create_project_5.png)

> Do not use a priority label, the Component or WP leads will rank the tasks/issues from the highest priority to the lowest priority, the ranking of the tasks/issues represent the priority ranking.
***
<br />
<br />
<br />

## 6. Pushing an issue to the 'Soilwise Project Backlog' and further describing the issue
It is important that all **"larger"** issues/tasks (**more than 3-days development work**) are pushed to the 'Soilwise Project Backlog'.
This is done by:
- selecting the issue in the repository, 
- in the right border select the 'Projects' bar
- select the "Soilwise Project Backlog"

![push_issue_to_backlog.png](push_issue_to_backlog.png)

The "Soilwise Project Backlog" can now also be found in the list of projects

![push_issue_to_backlog_1.png](push_issue_to_backlog_1.png)

A last step consists of adding information to the issue in the "Soilwise Project Backlog":
- go to the "Soilwise Project Backlog" via the "Projects" icon in the upper bar
- select the "Soilwise Project Backlog"
- select the specific issue
- a window will appear with information logged to the issue
- in the right panel under "Projects" add information relates to 
  - Status (Todo, In Progress, QA or Done, this can also be done by moving the issue to a certain column in the Kanban board)
  - WP (WP2, WP3 or WP4)
  - interaction (interaction needed (= interaction is needed with another team/component), no interaction)
  - Startdate
  - Enddate

![push_issue_to_backlog_2.png](push_issue_to_backlog_2.png)

> There is **no inheritance for issues over multiple projects**, this implies status and additional information about an issue/task must also be updated in the "Soilwise Project Backlog" project!!

***
