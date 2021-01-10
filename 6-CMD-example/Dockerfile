
###   6-Example  -    Dockerfile with CMD instruction only  

###############################         START     #########################

## Here the  base image is CENTOS
FROM centos

RUN yum install -y nano

## Last CMD instruction of a Dockerfile will be executed if there is more than one !!

CMD echo Bye from SHELL CMD instruction   ## This is a Shell form     
CMD ["echo", "Hello from EXEC CMD instrution"] ## This is EXECUTE form


###############################         END       #########################