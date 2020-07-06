# task1
automation for continuous integration and contiguous deployment
JOB#1
If Developer pushes to dev branch then Jenkins will fetch from dev and deploy on the dev-docker environment.
JOB#2
If Developer pushes to master branch then Jenkins will fetch from master and deploy on the master-docker environment.
both dev-docker and master-docker environments are on different docker containers.
JOB#3
Manually the QA team will check (test) for the website running in the dev-docker environment. If it is running fine then Jenkins will merge the dev branch to master branch and trigger #job 2
To start with the following task we need some prerequisites
Install Git Bash in windows
Make a VM on oracle VM virtual machine
Configure yum for AppStream, BaseOS, docker, Jenkins
Install docker using command #yum install docker-ce — nobest
Install Jenkins using command #yum install jenkins
systemctl start docker
systemctl start jenkins
we can access jenkins WebUIat IP:8080
Now Let’s start to work on our task:-
For full article check out the following link
https://medium.com/@manishdwarkas912/automation-for-continuous-integration-and-continuous-deployment-a99f1cfd6b10?source=friends_link&sk=f056b67cb00fe203455d281efabed3ac
