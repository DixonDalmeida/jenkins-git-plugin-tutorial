# Git Jenkins Integration

## Table of Contents:

* Objective 
* Steps
* Output

### Objective:
Create a Jenkins job to Download Code from Git Repository.

Condition: Only when there is a change in Git Repository Code Base

#### Steps:

* Login in to Jenkins
* Click on Jenkins -> Create New Item -> Free style Job 
* Click on Save
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Scenario%20101%20-%20Git/Create%20Job.png "Create Job")

* Scroll down to Source Code Management
* Select the checbox Git


* Add the Repository URL
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Scenario%20101%20-%20Git/Add%20Repositoy%20URL.png "Create Job")
* Click on Add Credentials
* Add Git Credentials
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Scenario%20101%20-%20Git/Add%20Git%20Credentials%20To%20Jenkins.png "Create Job")
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Scenario%20101%20-%20Git/Add%20Git%20Credentials%20To%20Jenkins%20Job.png "Create Job")

* Select the repository branch
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Scenario%20101%20-%20Git/Select%20Git%20Branch.png "Create Job")

* Scroll Down to Build Triggers
* Add the cron the Job in the Schedule
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Scenario%20101%20-%20Git/Schedule%20the%20Polling.png "Create Job")

* Click on  Save


#### Output:

Jenkins Job Checks, if there are Changes in Repository.
If there are new changes comitted, Job pulls new changes from the Git Repository


[Job Build Logs](https://github.com/starlord-dixon/Jenkins-Git-Plugin-Tutorial/tree/master/Scenario%20101%20-%20Git/download-repo-git/builds)
