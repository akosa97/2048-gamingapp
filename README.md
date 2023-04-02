I completed a project where I containerized a game application using Docker, deployed it on an Amazon EC2 instance, and then on AWS Elastic Beanstalk. Here are the key steps I followed:

Installed Docker on an Amazon EC2 instance.
Created a Dockerfile with the necessary steps to install the game application and dependencies, and expose port 80.
![nano Dockerfile](https://user-images.githubusercontent.com/91312467/229350194-6ad7850b-8bf2-4dec-bb29-abd0cc2c4939.jpg)

Built a Docker image from the Dockerfile using the docker build command.
![build docker image](https://user-images.githubusercontent.com/91312467/229350355-11b13dbe-d606-4bf3-8d57-5035d50b2bd9.jpg)

Created a Docker container from the image using the docker run command.
![docker run](https://user-images.githubusercontent.com/91312467/229350440-76d93931-c983-457c-9288-3ee0a06cac22.jpg)

Verified that the game application was accessible via the EC2 instance's public IP address and port 80.
![game running on port 80](https://user-images.githubusercontent.com/91312467/229350490-2718f34f-766f-4e32-844f-ee976d767f2f.jpg)
 
Uploaded the Dockerfile to AWS Elastic Beanstalk to deploy the containerized game application.
Configured Elastic Beanstalk environment settings and launched the application.
![elasticbeanstalk](https://user-images.githubusercontent.com/91312467/229350531-8b95c5e7-b9e3-4fc5-bbfa-b2cce954199c.jpg)

Verified that the game application was accessible through the Elastic Beanstalk environment URL.
![elasticbeanstalkwebsite](https://user-images.githubusercontent.com/91312467/229350519-f9210c4b-be7c-4fe8-bfcd-af552d9ec885.jpg)

By completing this project, I gained hands-on experience with containerization, Docker, AWS EC2, and Elastic Beanstalk.
