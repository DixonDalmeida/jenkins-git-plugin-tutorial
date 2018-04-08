# Git Jenkins Integration
### Scenario 1:
Checkout When Changes are Comitted on to Git

#### Steps:

* Login in to Jenkins
* Click on Jenkins -> Create New Item -> Free style Job 
* Click on Save
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Create%20Job.png "Create Job")

* Scroll down to Source Code Management
* Select the checbox Git


* Add the Repository URL
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Add%20Repositoy%20URL.png "Create Job")
* Click on Add Credentials
* Add Git Credentials
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Add%20Git%20Credentials%20To%20Jenkins.png "Create Job")
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Add%20Git%20Credentials%20To%20Jenkins%20Job.png "Create Job")

* Select the repository branch
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Select%20Git%20Branch.png "Create Job")

* Scroll Down to Build Triggers
* Add the cron the Job in the Schedule
![Alt text](https://github.com/starlord-dixon/Jenkins-Pipeline-Plugin-Tutorial/blob/master/images/Schedule%20the%20Polling.png "Create Job")

* Click on  Save


#### Output:

Jenkins Job Checks, if there are Changes in Repository.
If there are new changes comitted, Job pulls new changes from the Git Repository