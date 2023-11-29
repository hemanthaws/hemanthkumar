# Docker
**#Dockerize NodeJs & ReactJS application (must be multi-stage & lightweight docker image).**
**#Setup it on Linux System with docker-compose. Expose it via Nginx reverse proxy**

#Creating in the docker file to build React App and Serve React App with nginx 

#Going to setup on ubuntu 20.04 version with Docker-Compose.
# step-1: creating instance and depolying ubuntu 20.04 on that instance.
# Below commands are to install docker and docker-compose on ubuntu
#sudo apt-get update

#sudo apt-get install -y docker.io

#sudo apt-get install -y docker-compose

# Below command to Expose it via Nginx reverse proxy

#sudo apt-get install -y ngnix
# Creating a nginx configuration file and save that file in specfic path 
# For example: /etc/nginx/sites-available/reverse-proxy
# The code as been stored in "reverse-proxy file" 
# Create a symbolic link to enable the site
#sudo ln -s /etc/nginx/sites-available/reverse-proxy /etc/nginx/sites-enabled
# Then Restart the Nginx by using below command
#sudo service nginx restart



# GitLab CI/CD Pipeline for Deployment:

# GitLab Runner Setup:

#Install GitLab Runner on your VM.

#Register the runner with your GitLab instance.

# .github-ci.yml Configuration:

#Define stages for your pipeline (e.g., build, test, deploy).

#Utilize different jobs for each stage, including deployment.

#Use environment variables for sensitive information.
