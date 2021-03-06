# Project Management
This file presents how I managed the project. In other words, how I distrubuted type and amount of work depending on project phase and circumstances. It also highlights the use of management tools like Jira and Gitlab.  

## List of contents
* [Planning, organisation](#planning-and-organisation) and their phases:  
	* [Summer work](#summer-work)  
	* [Challenge week work](#challenge-week-work)  
	* [Completing assignments of other modules](#completing-assignments-of-other-modules)  
	* [From 16th November till interim interview](#from-16th-november-till-interim-interview)  
	* [From interim interview till the final report](#from-interim-interview-till-the-final-report)  
* [Managing risks](#managing-risks)  
    * [Lack of motivation](#lack-of-motivation)  
	* [Dwelling on details](#dwelling-on-details)  
* [Use of Gitlab](#use-of-gitlab)  
* [Use of Jira](#use-of-jira)  


## Planning and organisation
My organisation of the project could be split into several phases:  

![IMAGE DIDNT SHOW](https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/cumulative_flow_report.png)  


### Summer work  
* background reading:
    * [Familiarizing with graph theory](https://cseejira.essex.ac.uk/browse/A301079-6)  
    * [Identifying and understanding algorithms](https://cseejira.essex.ac.uk/browse/A301079-2)  
    * [Recognizing and evaluating methods of teaching them](https://cseejira.essex.ac.uk/browse/A301079-3)  
	* [Reading Qt documentation](https://cseejira.essex.ac.uk/browse/A301079-4)  
	* [Finding relevant Qt examples](https://cseejira.essex.ac.uk/browse/A301079-5)  
	* I undertook investigation to verify the use case of MST as a near-optimal route.  
	I was intrigued by the claims that MST can be used to find near-optimal route from the article called “An Application of Minimum Spanning Trees to Travel Planning” (2010) by L Fitina et al. I wrote a code to verify accuracy of few statements from that article and presented my findings on page 14 of [Project introduction document](./docs/Project%20introduction.docx).  
	![IMAGE DIDNT SHOW](https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/mst_use_case_investigation_results.png)  
* tinkering with researched resources, trying to implement foundations for drawing a graph and implementing the first algorithm (e.g. drawing circles and lines to represent graph vertices and edges, implementing text-input fields for edge-weights).  


### Challenge week 
During the challenge week I accomplished the following tasks:  
* [Formulated project objectives](https://cseejira.essex.ac.uk/browse/A301079-7)  
	These can be viewed in the [Project introduction document](./docs/Project%20introduction.docx)  
* [Documented summer coding](https://cseejira.essex.ac.uk/browse/A301079-12)  
* [Added facility to create and modify a graph](https://cseejira.essex.ac.uk/browse/A301079-10)  
* [Implemented a single algorithm](https://cseejira.essex.ac.uk/browse/A301079-11)  
* Created extensive [Project introduction document](./docs/Project%20introduction.docx)  

At the end of the challenge week I created [0.1.0 release](https://cseejira.essex.ac.uk/projects/A301079/versions/14120) on Jira which contains all issues completed up to the challenge week:  

<kbd><img src="https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/challenge_week_issues.png" alt="IMAGE DIDNT SHOW"></kbd>  


### Completing assignments of other modules
Capstone project has no limit in terms of progress that can be made. So I decided to strategically postpone further work on it until I complete (or almost complete) all available assignments of other modules and afterwards focus entirely on the project. This way I could utilize all remaining time without fear of not giving other modules enough attention. This period lasted around a month, giving me another full month of project work before the interim interview.  
 
 
### From 16th November till interim interview
During this time I spent most of my free time working on the project and implemented most of the program functionality, including:  
* algorithm selection facility  
* 4 new algorithms  
* custom graph saving/loading  
* selectable preset graphs  

 I slightly transitioned away from carefully considering every code addition (which I did during early design stage) into adding sheer amount of features. I documented each step of the progress by creating separate Jira issue for every task. Every time I marked an issue as "done", I wrote a short comment with links to relevant Gitlab commits, often with an additional image of what was implemented, or few lines of code (that fixed a bug for example). Here's an example of the comment added when [priority queue task issue](https://cseejira.essex.ac.uk/browse/A301079-75) was marked as "done":  

<kbd><img src="https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/jira_issue_done_comment_pic_example.png" alt="IMAGE DIDNT SHOW"></kbd>  

...and here's an example of the comment added after a [sub-window bug issue](https://cseejira.essex.ac.uk/browse/A301079-80) was fixed and marked as "done":  

<kbd><img src="https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/jira_issue_done_comment_pic_example_2.png" alt="IMAGE DIDNT SHOW"></kbd>  

The list of Jira issues created during this time can be viewed [here](https://cseejira.essex.ac.uk/browse/A301079-91?jql=project%20%3D%20A301079%20AND%20status%20%3D%20Done%20AND%20created%20%3E%3D%202020-11-16%20AND%20created%20%3C%3D%202020-12-18).  

[Task issues](https://cseejira.essex.ac.uk/browse/A301079-52?jql=project%20%3D%20A301079%20AND%20issuetype%20%3D%20Task%20AND%20status%20%3D%20Done%20AND%20created%20%3E%3D%202020-11-16%20AND%20created%20%3C%3D%202020-12-18) included:  

<kbd><img src="https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/task_issues.png" alt="IMAGE DIDNT SHOW"></kbd>  

[Bug issues](https://cseejira.essex.ac.uk/browse/A301079-91?jql=project%20%3D%20A301079%20AND%20issuetype%20%3D%20Bug%20AND%20status%20%3D%20Done%20AND%20created%20%3E%3D%202020-11-16%20AND%20created%20%3C%3D%202020-12-18) included:  

<kbd><img src="https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/bug_issues.png" alt="IMAGE DIDNT SHOW"></kbd>  


### From interim interview till the final report
During that time I considered the development to be finished and made only minor changes to the code (fixing small bugs/typos). I focused on producing deliverables (abstract, poster, final report), and the coursework of other modules.  


## Managing risks

#### [Lack of motivation](https://cseejira.essex.ac.uk/browse/A301079-9)  
Online learning doesn't help to stay focused on studying. It makes it easier to get distracted. I tried to stay away from procrastination by frequently updating and checking Kanban board, and also by using physical board to keep track of important dates and tasks:   

![IMAGE DIDNT SHOW](https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/board_.png)  

#### [Dwelling on details](https://cseejira.essex.ac.uk/browse/A301079-41)  
Polishing details before creating key program features could result in the following effect:  

![IMAGE DIDNT SHOW](https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/risk_horse.png)  

I prioritized implementing all algorithms first instead of trying to make each algorithm perfect from the start.  

## Use of Gitlab 
I tried to keep reasonable ratio of commits per amount of work done, being aware that infrequent commits would make it hard to track the changes and too frequent commits would be inefficient. As shown on image below, I used descriptive commit names, which helps to track the changes (and to reference them in Jira).  

<kbd><img src="https://raw.githubusercontent.com/michalmonday/files/master/ce301%20Capstone%20project/pics/mvp/gitlab_commits.png" alt="IMAGE DIDNT SHOW"></kbd>  

## Use of Jira
Very often while working on something I get multiple ideas on what changes to make. Using Jira and creating tasks for such ideas helped me to avoid forgetting them over time. Additionally, having saved issues in the "backlog", "selected for development" or "in progress" columns of the Kanban board is a good motivational factor to get them done. Throughout this document I used hyperlinks to reference Jira issues. 












