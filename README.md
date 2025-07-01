# Node.js-Login-Register-App-Microservice
Node.js Login-Register App-Microservice


# Containerizing a Node.js Login and Register App with Docker — The First Step in Microservices Deployment


Steps:
1. Create a Login App

1. Create a index.html file
a. Create a index.html file using vi index.html in /public folder.
b. Add the below given Code in that file.

2. Create an app.js file
a. Create a app.js file using vi app.js.
b. Add the below given code in the app.js file

3. Create Dockerfile for Login App
a. Create a Dockerfile using vi Dockerfile
b. Add the below given code in Dockerfile.

4. Build Image using Dockerfile
a. Build the Docker image using the below given command.
docker build -t ekangaki/login-app:v1 .
########################################

2. Create a Register App

1. Create a index.html file
a. Create a index.html file using vi index.html in /public folder.
b. Add the below given Code in that file.

2. Create an app.js file
a. Create a app.js file using vi app.js.
b. Add the below given code in the app.js file

3. Create Dockerfile for Login App
a. Create a Dockerfile using vi Dockerfile
b. Add the below given code in Dockerfile.

4. Build Image using Dockerfile
a. Build the Docker image using the below given command.
docker build -t ekangaki/register-app:v1 .
#########################################

3. Push the images to the Docker Hub
a. login to your DockerHub

$ docker push ekangaki/login-app:v1
$ docker push ekangaki/register-app:v1


