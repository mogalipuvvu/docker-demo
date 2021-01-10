
###   9-Example  -    Dockerfile - ENTRYPOINT with shell script  
###############################         START     #########################

## Here the  base image is CENTOS
FROM centos

## some installation as needed for our project
RUN yum install -y tree
RUN mkdir training-dir

### This is important to copy the shell script from our host computer 

COPY docker-entrypoint.sh /usr/local/bin/


ENTRYPOINT  ["echo", " Hello World" ]

## the above entrypoint will be ignored and the following one is considered.
ENTRYPOINT  ["docker-entrypoint.sh", "This is coming from ENTRYPOINT " ]

###############################         END       #########################

