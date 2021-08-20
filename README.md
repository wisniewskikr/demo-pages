SPRING BOOT MVC AND THYMELEAF WITH PAGES
========================================


LOCALHOST URL
-------------

* **URL**: http://localhost:8080


DESCRIPTION
-----------

#####Goal
The goal of this project is to show to create application with two related pages using technologies Spring Boot MVC and Thymeleaf. 

#####Details
This project consists following pages:
* Input Page: this page contains input filed with name;
* Output Page: this page contains text "Hello World" + name from Input Page.

#####Used technologies:
* **BE**: Spring Boot MVC
* **FE**: Thymeleaf


IMPLEMENTATION
-----------

Implementation details:
* Create class InputCommand.java;
* Create class InputController.java;
* Create file "input.html";
* Create class OutputCommand.java;
* Create class OutputController.java;
* Create file "output.html".
  

LAUNCH
------

To launch project please run following class: 
* Application.java

You can also launch project using Maven command:
* mvn spring-boot:run -Dspring.thymeleaf.cache=false


USAGE
-----

Link to main UI:
* http://[server]

DOCKER
------

Commands about images:
* docker images: list of all images
* docker rmi <IMAGE ID>: remove image with specific id

Command about container:
* docker ps: list of active containers
* docker ps -a: list of all containers
* docker stop <CONTAINER ID>: stop container with specific id
* docker start <CONTAINER ID>: start container with specific id
* docker rm <CONTAINER ID>: remove container with specific id

Commands to build, run and deploy Docker image:
* docker build -t wisniewskikr/demo-pages .
* docker run -p 8080:8080 wisniewskikr/demo-pages
* docker push wisniewskikr/demo-pages

Docker page:
https://hub.docker.com/
