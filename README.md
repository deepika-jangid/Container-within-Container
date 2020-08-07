# Container-within-Container
  In this project, I have achieved containerization-within-container. Yes, you read it right, <b>Containerization-within-container</b>. Now you are wondering that isn't it           possible to do so ? So, Yes dear it is possible to do and here I will teach you the step-by-step procedure of how I build this interesting project. 
  
# Steps we will follow to accomplish this task are as follows-
1. First, we will create a Jenkins image on our own using Dockerfile.
2. When we launch this image, it should automatically starts Jenkins service in the container.
3. Create a job chain of job1, job2 and job3 using a build pipeline plugin in jenkins.  
4. <b>Job1</b> : Pull  the Github repo automatically when some developers push repo to Github.
5. <b>Job2</b> : By looking at the code or program file, Jenkins should automatically start the respective language interpreter install image container to deploy code ( eg. If        code is of  HTML, then Jenkins should start the container that has HTML already installed ).
6. <b>Job3</b> : Test your app if it is working or not.
7. If not working, then send email to developer with error messages.

# How to create Jenkins Image using DockerFile?
* Create a folder/dir with any name you want say '/ws' on your system. 
* Create a file must be named as 'Dockerfile' in that folder/dir.
* Open the Dockerfile file and write the following commands in it:-
  
  ![](Images/Dockerfile.png)
  
  This will create your own customize jenkins image having docker configured in it or you can pull my jenkins image from https://hub.docker.com/u/deepika1999 <a         href="https://hub.docker.com/u/deepika1999">My Docker Hub Account</a>.


  



  
