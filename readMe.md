# 🤵 John Bonnett

<p align="center">

![](https://camo.githubusercontent.com/992babdffd8c74a1502de375fbdf7e4d54773242/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f53576f536b4e36447854737a71494b4571762f67697068792e676966)

### Dockerizing Angular - 4

This is a Full Stack Website Development project. Developing an **online Angular app** to be deployed thru a Docker container on an AWS EC2 instance. A cloud virtual machine, so that other developers can access and modify it if required.

This app connects the frontend to a json-server. A Devlopment Dockefile.dev for local use and a Production Dockerfile.prod for deployment are created. Also created are Docker-compose file for both production and development.
The code and images are stored here and also on Docker Hub. 

- **The tools used for development are:** ```Visual Studio Code```, ```Docker```, ```HTML/CSS```, ```.Angular CLI``` ```.Github``` ```.Github Project Manager```, ```NodeJS```, ```json-server```


**Required dependencies to development this app:**

  > 1. Docker Hub.
  > 2. json-server.
  > 3. git bash terminal.
  > 4. SSH.
  > 5. AWS EC2 instance.
  > 6. NgINX server.
  
  **Required tools to check data while creating data flow:**
  
  > 1. Docker desktop.
  > 2. Browser development tools Chrome and Firefox.

**Required commands to run front-end for this app:**

  > 1. npm install.
  > 2. ng serve.
  
  **Required commands to run back-end for this app:**

  > 1. npm run server.

  **Required commands to build the development & production container for this app:**

  > 1. npm install.
  > 2. ng serve.

**REQUIRED OBJECTIVES MET:**

  > 1. The source codes is tracked on this GitHub repositories.
  > 2. Document the tracked files that are ignored during the final push to the GitHub repository.
  > 3.  Submission of GitHub repository link is mandatory in order to track your task.
  > 4.  The step-by-step process involved in completing this task documented below.

---
**THE DEVELOPMENT STEPS:**

- [Deployed Angular Container to AWS ](#markdown)
- [Stages to be developed](#markdown-syntax-extensions)
  - [Create dynamic Angular app working with json-server as backend feature ](#markdown-extended-mde)
  - [Create dev container and production container.](#markdown-extended-mde) 
  - [Create a docker-compose-prod file for production deployment to AWS.](#markdown-extended-mde)
- [Container repositories](#markdown-syntax-extensions)
  - [Upload Images to Docker Hub ](#markdown-extended-mde)
  - [Upload Images to GitHub to Docker Hubs packages](#markdown-extended-mde) 
  - [Create a docker-compose-prod file for production deployment to AWS.](#markdown-extended-mde)
- [AWS EC2 Instance](#markdown-syntax-extensions)
   - [Install AWs Cli](#markdown-extended-mde)
  - [install git-bash](#markdown-extended-mde) 
  - [Launch an EC2 AWS Instance](#markdown-extended-mde)
    - [name - my-ec2-instance](#markdown-extended-mde)
     - [select linux 64bit x86 - hardware](#markdown-extended-mde)
      - [Instance type - t2.micro](#markdown-extended-mde)
      - [Generate new key pair use .rsa and .pem](#markdown-extended-mde)
         - [Download  file to mykeys-folder for SSH .pem login](#markdown-extended-mde)
- [Load Dependencies for instance](#markdown-syntax-extensions)
  - [install nodejs ](#markdown-extended-mde)
  - [install Docker](#markdown-extended-mde)
  - [Use SSH command to upload image files to instance](#markdown-extended-mde) 

- [To test container in browser](#markdown-syntax-extensions)
  - [set Inbound security rules](#markdown-extended-mde)
  - [Port range - 80:80-9999](#markdown-extended-mde)
  - [Custom TCP Anywhere - IPV4](#markdown-extended-mde)   
  
---

Credit: [John Bonnett]

Last Edited on: 06/026/2023

