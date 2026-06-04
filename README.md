# frontend-docker-app


# Frontend Website Deployment using Docker and Amazon EC2

## Project Overview

This project demonstrates the deployment of a professional frontend website using Docker and Amazon EC2. The website was developed using HTML, CSS, and JavaScript, containerized using Docker with Nginx as the web server, and deployed on an AWS EC2 instance.

The deployment process follows a modern container-based workflow where source code is maintained in GitHub, deployed through Docker containers, and served publicly through Amazon EC2. The application can be easily updated by pushing changes to GitHub, pulling the latest code on EC2, rebuilding the Docker image, and restarting the container.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Docker
* Nginx
* Git
* GitHub
* Amazon EC2

## Features

* Professional and responsive user interface
* Home Section
* About Section
* Services Section
* Contact Section
* Docker containerization
* Nginx web server integration
* GitHub-based source code management
* Cloud deployment on AWS EC2
* Easy update and redeployment workflow

## Project Architecture

Developer
→ GitHub Repository
→ Amazon EC2 Instance
→ Docker Container
→ Nginx Web Server
→ Frontend Website

## Deployment Workflow

1. Developed the frontend website locally.
2. Created a Dockerfile using the Nginx base image.
3. Built and tested the Docker image locally.
4. Pushed source code to GitHub.
5. Launched and configured an Amazon EC2 instance.
6. Installed Docker and Git on EC2.
7. Cloned the GitHub repository on EC2.
8. Built the Docker image on EC2.
9. Deployed the website using a Docker container.
10. Accessed the application through the EC2 Public IP.
11. Updated the application using GitHub and Git Pull.
12. Rebuilt and redeployed the Docker container successfully.

## Docker Commands Used

```bash
docker build -t frontend-app .
docker run -d -p 80:80 --name frontend-container frontend-app
docker ps
docker logs frontend-container
docker stop frontend-container
docker start frontend-container
docker restart frontend-container
docker rm frontend-container
```

## Git Commands Used

```bash
git clone https://github.com/rajyalakshmi778/frontend-docker-app.git
git add .
git commit -m "Initial Commit"
git push origin main
git pull origin main
```

## Live Deployment

Frontend website deployed using Docker, Nginx, and Amazon EC2.

GitHub Repository:
https://github.com/rajyalakshmi778/frontend-docker-app

AWS EC2 Public URL:
http://15.206.129.159

## Outcome

Successfully containerized and deployed a frontend website using Docker and Nginx on an Amazon EC2 instance. The project demonstrates Git-based version control, Docker container management, cloud deployment, application updates through Git Pull, and production-style hosting using AWS infrastructure.
