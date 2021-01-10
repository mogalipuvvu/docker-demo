
###   8-Example  -    Dockerfile - Both ENTRYPOINT with CMD present! 
###############################         START     #########################

## Here the  base image is CENTOS
FROM centos
RUN yum install -y tree

#From the following Entrypoint "echo" is executable

ENTRYPOINT  [ "echo" , "Hello from ENTRYPOINT  " ]

## Here the following two parameters from CMD instruction are default params
CMD ["  Hello from CMD  " , "  Bye from CMD  "]

## Make sure that also try with and without additional params at command line when docker run

###############################         END       #########################

