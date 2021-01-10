
###   7-Example  -    Dockerfile with ENTRYPOINT instruction   

###############################         START     #########################

## Here the  base image is CENTOS
FROM centos
RUN yum install -y tree

## Last ENTRYPOINT instruction of a Dockerfile will be executed if there is more than one !!

ENTRYPOINT  [ "echo" , "Hello from ENTRYPOINT" ]
ENTRYPOINT  [ "echo" , "Message from ENTRYPOINT " ]

###############################         END       #########################


