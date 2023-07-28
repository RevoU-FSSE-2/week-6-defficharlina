<h3 align="center">
Hi there, I'm Deffi 👋
</h3>

### 🤝 Connect with me:

[Linkedin](https://www.linkedin.com/in/defficharlinasari/)
[Instagram](https://www.instagram.com/defficharlina/)
- 💬 If you have any question/feedback, please do not hesitate to reach out to me!

# Project Description
This project is about simple node.js project can be run inside docker container


## Skill
1. Docker

    Docker is a platform designed to help developers build, share, and run modern applications. We handle the tedious setup, so you can focus on the code.


## Dev Environment Setup
1. Docker

    Install Docker, please visit [Docker](https://www.docker.com/)

2. Git Bash

    For installation, please visit [Git Bash](https://git-scm.com/downloads)

3. Visual Studio Code

    For installation, please visit [Visual Studio Code](https://code.visualstudio.com/)


## Installing Docker and WSL
1. Click Download Docker Dekstop Windows

  <p align="center">
    <img src="images/docker 1.JPG" width="600">
  </p>

2. Install Docker

  <p align="center">
    <img src="images/docker 2.JPG" width="450">
  </p>

3. You can install WSL or update WSL

  <p align="center">
    <img src="images/check docker wsl.JPG" width="450">
  </p>

## Create files 
1. Clone repo https://github.com/RevoU-FSSE-2/week-6-defficharlina
2. Download simple Node.js project from https://gist.github.com/berdoezt/e51718982926f0caa3fcd8ed45111430 and save with
   name server.js in Visual Studio Code

   <p align="center">
    <img src="images/server js.JPG" width="450">
   </p>

3. Create file package.json

   <p align="center">
    <img src="images/package json.JPG" width="450">
   </p>

4. Create Dockerfile

   <p align="center">
    <img src="images/dockerfile.JPG" width="450">
   </p>

5. Create .dockerignore

   <p align="center">
    <img src="images/dockerignore.JPG" width="450">
   </p>

## Build and run image
1. Build image with terminal and using command **docker build . -t your_image_name**
2. Check our image using command **docker images**

   <p align="center">
    <img src="images/build image.JPG" width="450">
   </p>

3. We can check our image in docker dekstop

   <p align="center">
    <img src="images/docker dekstop.JPG" width="450">
   </p>

4. And then run the image using command **docker run -p your-localport:app-port your_image_name**

   <p align="center">
    <img src="images/docker run.JPG" width="450">
   </p>

5. Let's check the result on localhost

   <p align="center">
    <img src="images/localhost.JPG" width="450">
   </p>

## The last step's push to Github all files that we created and finished
