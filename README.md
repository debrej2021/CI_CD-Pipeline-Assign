# CI_CD-Pipeline-Assign


I created a Ubuntu EC2 Instance to install Jenkins The IP Address of the EC2 is http://52.36.205.57/
Jenkins cannot be installed in the latest Ubuntu version which is 24 hence had to use docker container to install Jenkins and run Jenkins 
I was able to have jenkins run on http://52.36.205.57:8080 

https://github.com/debrej2021/CI_CD-Pipeline-Assign/tree/master contains the screen shots and sample application.py file 
I created another simple Python application repo as https://github.com/debrej2021/my-python-project/tree/master ( I am putting master since the master contains the main file , it also contains the jenkins file and application file with a simple fask Web page )

I included the relevant steps in Jenkinsfile to have the relevant steps . 

I am also including some successful run console output as in 12 and 13 . 

At last it is failing for some docker issue as I want to run the application on Docker . 

I cannot fork the repo since I am not part of any associations 

All the relavant screen shots also included 

I created a job MyPythonProjectJob to have the pipeline trigerred from the Jenkins file 

I added a Webhook to trigger a new build when ever changes pushed to repo 
 I also configured the email to send out notifications . 


**PLEASE NOTE - I AM NOT INCLUDING ANY PASSWORDS / USERIDS For safety , if required I can send through . right now uploading on Vlearn
http://54.203.39.4:8080/