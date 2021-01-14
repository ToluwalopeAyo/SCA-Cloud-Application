# SCA-Cloud-School-Application

This repo contains the files I used to create the webpage and the Dockerfile

*Webpage Using Dockerfile*

_Step 1_

Create the HTML and Dockerfile in a folder

_Step 2_

Open Powershell and cd into the folder

_Step 3_

`docker build -t webserver-image . `

_Step 4_

`docker run -dp 8080:80 webserver-image`

The website will be displayed on `http://localhost:8080`

Link to docker image on dockerhub: https://hub.docker.com/repository/docker/tolulopeayo/web
