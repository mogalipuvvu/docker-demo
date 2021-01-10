
###   5-Example  -    Dockerfile - Setting a USER   

###############################         START     #########################

## Here the  base image is CENTOS
FROM centos

## First make sure that user exists, so creating a user
RUN useradd test-user-projectA

## Most of the times it is not required to have root privileges 
## set the non-root user
USER test-user-projectA
###############################         END       #########################
