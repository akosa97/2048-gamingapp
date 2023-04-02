I completed a project where I containerized a game application using Docker, deployed it on an Amazon EC2 instance, and then on AWS Elastic Beanstalk. Here are the key steps I followed:

    Installed Docker on an Amazon EC2 instance.
    Created a Dockerfile with the necessary steps to install the game application and dependencies, and expose port 80.
![nano Dockerfile](https://user-images.githubusercontent.com/91312467/229350194-6ad7850b-8bf2-4dec-bb29-abd0cc2c4939.jpg)

    Built a Docker image from the Dockerfile using the docker build command.
    Created a Docker container from the image using the docker run command, and verified that the game application was accessible via the EC2 instance's public     IP address and port 80.
    Uploaded the Dockerfile to AWS Elastic Beanstalk to deploy the containerized game application.
    Configured Elastic Beanstalk environment settings and launched the application.
    Verified that the game application was accessible through the Elastic Beanstalk environment URL.

By completing this project, I gained hands-on experience with containerization, Docker, AWS EC2, and Elastic Beanstalk.
