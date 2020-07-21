# tomcat-webserver
A basic running a web app on Tomcat using Docker

# Steps
* Install [Docker](https://docs.docker.com/install/).
* Copy tomcat-webserver folder .  
* cd 'tomcat-webserver'
* $docker build -t mywebapp .
* $docker run -p 80:8080 --name vinaywebapp mywebapp
* http://localhost:80

