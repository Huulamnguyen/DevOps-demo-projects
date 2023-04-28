## DevOps-demo-projects
a collection of all DevOps demo and challenges

## Tables of Contents:
1. [Deploy Java React with Gradle and Digital Ocean](#deploy-java-react-with-gradle-and-digital-ocean)
2. [Deploy Node App with Digital Ocean](#deploy-node-app-with-digital-ocean)
3. [Publish Java Gradle Artifact to Nexus](#publish-java-gradle-artifact-to-nexus)
4. [Use Docker for local development](#user-docker-for-local-development)
5. [Docker Compose - Run multiple Docker container](#docker-compose-run-multiple-docker-container)
6. [Dockerized Nodejs application and push to private Docker](#Dockerized-nodejs-application-push-to-private-docker)
7. [Deploy Docker application on a server with Docker Compose](#deploy-docker-app-on-server-with-docker-compose")
8. [Persist data with Docker Volumes](#Persist-data-with-Docker-Volumes)
9. [Create Docker repository on Nexus and push to it](#Create-Docker-repository-on-Nexus-and-push-to-it)
10. [Deploy Nexus as Docker container](#Deploy-Nexus-as-Docker-container)

-----
## Module 5: Cloud & Infrastructure as Service Basics with DigitalOcean
## 1. Deploy Java React with Gradle and Digital Ocean <a name="deploy-java-react-with-gradle-and-digital-ocean"></a>
### Demo Project:
- Create a server and deploy application on Digital Ocean
- File name: java-react-gradle-digital-ocean
- View Repo: https://github.com/Huulamnguyen/DevOps-demo-projects/tree/main/java-react-gradle-digital-ocean
### Technology used:
- Digital Ocean, Linux, Java, Gradle
### Project Description:
- Setup and configure a server on Digital Ocean
- Create and configure a new Linux user on the Droplet (security best practices)
- Deploy and run a Java application on Droplet
### Source:
- Module 5: Cloud & Infrastructure as Service Basics with DigitalOcean

-----
## 2. Deploy Node App with Digital Ocean <a name="deploy-node-app-with-digital-ocean"></a>
### Demo Project:
- Create a server and deploy Node application on Digital Ocean
- File name: bode-digital-ocean
- View repo: https://github.com/Huulamnguyen/DevOps-demo-projects/tree/main/node-digital-ocean
### Technology used:
- Digital Ocean, Linux, Node, npm
### Project Description:
- Setup and configure a server on Digital Ocean
- Create and configure a new Linux user on the Droplet (security best practices)
- Deploy and run a node application on Droplet
### Source:
- Module 5: Cloud & Infrastructure as Service Basics with DigitalOcean

-----
## Module 6: Artifact Repository Manager with Nexus
## 3. Publish Java Gradle Artifact to Nexus <a name="publish-java-gradle-artifact-to-nexus"></a>
### Demo Project:
- Create a server and deploy Node application on Digital Ocean
- File name: java-gradle-nexus
- View repo: https://github.com/Huulamnguyen/DevOps-demo-projects/tree/main/java-gradle-nexus
### Technology used:
- Digital Ocean, Linux, Nexus, Gradle
### Project Description:
- Setup and configure a server on Digital Ocean
- Install Nexus on droplet
- Configure `gradle.build` file and Publish artifact to Nexus
### Source:
- Module 6: Artifact Repository Manager with Nexus

-----
## Module 7: Containers with Docker 
## 4. Use Docker for local development <a name="user-docker-for-local-development"></a>
### DemoProject:
- Use Docker for local development
- File name or repo: developing-with-docker
### Technology used:
- Docker, Node.js, MongoDB, MongoExpress
### Project Description:
- Create Docker file for Nodejs application and buildD ocker image
- Run Nodejs application in Docker container and connect to MongoDB database container locally
- Also run Mongo Express container as a UI of the MongoDB database
### Source:
- Module 7: Containers with Docker

-----
## 5. Docker Compose - Run multiple Docker container <a name="docker-compose-run-multiple-docker-container"></a>
### DemoProject:
- Docker Compose - Run multiple Docker container
- File name or repo: developing-with-docker
### Technology used:
- Docker, Node.js, MongoDB, MongoExpress
### Project Description:
- Write Docker Compose files to run MongoDB and MongoExpress Containers
### Source:
- Module 7: Containers with Docker

-----
## 6. Dockerized Nodejs application and push to private Docker <a name="Dockerized-nodejs-application-push-to-private-docker"></a>
### Demo Project:
- Dockerized Nodejs application and push to private Docker registry Amazon ECR 
- File name or repo: developing-with-docker
### Technologies used:
- Docker, Node.js, Amazon ECR
### Project Description:
- Write Dockerfile to build a Docker image for a Nodejs application
- Create private Docker registry on AWS (Amazon ECR)
- Push Docker image to this private repository
### Source:
- Module 7: Containers with Docker

-----
## 7. Deploy Docker application on a server with Docker Compose <a name="deploy-docker-app-on-server-with-docker-compose"></a>
### Demo Project:
- Deploy Docker application on a server with Docker Compose
- File name or repo: developing-with-docker
### Technologies used:
- Docker, Amazon ECR, Node.js, MongoDB, MongoExpress
### Project Description:
- Copy Docker-compose file to remote server
- Login to private Docker registry on remote server to fetch our app image
- Start our application container with MongoDB and MongoExpress services using docker compose
### Source:
- Module 7: Containers with Docker

-----
## 8. Persist data with Docker Volumes <a name="Persist-data-with-Docker-Volumes"></a>
### Demo Project:
- Persist data with Docker Volumes
- File name or repo: developing-with-docker
### Technologies used:
- Docker, Node.js, MongoDB
### Project Description:
- Persist data of a MongoDB container by attaching a Docker volume to it
### Source:
- Module 7: Containers with Docker

-----
## 9. Create Docker repository on Nexus and push to it <a name="Create-Docker-repository-on-Nexus-and-push-to-it"></a>
### Demo Project:
- Create Docker repository on Nexus and push to it
- File name or repo: developing-with-docker
### Technologies used:
- Docker, Nexus, DigitalOcean, Linux
### Project Description:
- Create Docker hosted repository on Nexus
- Create Docker repository role on Nexus
- Configure Nexus, DigitalOcean Droplet and Docker to be able to push to Docker repository
- Build and Push Docker image to Docker repository on  Nexus
### Source:
- Module 7: Containers with Docker

-----
## 10. Deploy Nexus as Docker container <a name="Deploy-Nexus-as-Docker-container"></a>
### Demo Project:
- Deploy Nexus as Docker container
- File name or repo: developing-with-docker
### Technologies used:
- Docker, Nexus, DigitalOcean, Linux
### Project Description:
- Create and Configure Droplet
- Set up and run Nexus as a Docker container
### Source:
- Module 7: Containers with Docker