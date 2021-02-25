# newrepo
### User Story
###Background of the problem statement:

 - M-theta Technology Solutions hired you as a DevOps Architect. It is undergoing an infrastructural change to implement DevOps to develop and deliver the products. Since M-theta is an Agile organization, they follow the Scrum methodology to develop the projects incrementally. Hence, the company wants to adopt Git as a Source Code Management (SCM) tool for faster integration of work and smooth transition into DevOps.

- So, as a DevOps Architect, you have been asked to build a branching model to demonstrate the Git Feature Branch Workflow for the company’s engineering team. In the branching model, you are required to create a Production branch which will act as the main (master) branch, an Integration branch which will again have two branches inside it namely Feature 1 and Feature 2, and a Hotfix branch which will be used for fixing any issues that could come up from Integration or Production branches.

![layout](/images/layout.jpg)

Goal:

Create a NewRepo in Git
Clone Repo
1.	Start with main branch
2.	Create with gitignore
3.	Create with Readme
4.	Create a HotFix branch
5.	Create Integration branch
6.	Create Feature1 branch 
7.	Create Feature2 branch
    i.	Merge Feature 1 & 2 to the Integration branch
    ii.	Commit some changes in the Feature 2 branch 
8.	Merge it into the Integration branch. 
    i.	Delete this branch once merging is complete
9.	Commit some changes in the Feature 1 branch and rebase it to the    
        Integration branch
10.	Merge the Integration branch into Hotfix and Production branch to update   
        these branches
11.	Commit some changes in Feature 1 branch, and then merge it into Integration, 
        Hotfix, and Production branch. 
    a.	Delete this branch once merging is complete
12.	Commit some changes in the Hotfix branch and merge it into the Production as 
    well as the Integration branch


