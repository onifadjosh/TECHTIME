# TECHTIME
An entry for a frontend job on talentplus 
 For a moment i was confused i heard dokerize, then i made research
 and contacted my Devops friends and they showed me the light.
 
 From research and discussions i kept hearing image, docker, container, containerize.
 
 Images are read-only template with instructions for creating a docker container
 often, an image is based on another image, with some additional customization.
 
 Container is like a runnable instance of an image.
You can create, start, stop, move, or delete a container using the docker API or CLI

STEPS I USED TO DOCKERIZE MY PROJECT
# I created a docker file with niginx image
#connected the project to docker file
#built docker image with current project
#to build docker image with the project we have to navigate into project folder
#to custom docker image name we have to add '-t' (docker build -t "type docker image name".)
