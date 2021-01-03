###   4-Example  -    Dockerfile - Setting  WORKing DIR    
#################################         START     ################ ############

## Here the  base image is CENTOS
FROM centos
RUN yum install -y tree

RUN mkdir training-dir


#### Setting working directory as learnings-demo
WORKDIR /learnings-demo

### learnings-demo will be created and set it as working directory
### That means all instructtions will be executed from here
### Observe that directories in your root!! 

COPY ./  ./

### Defining or Setting Environment variables

ENV X=10
ENV CITY=Austin-Texas
ENV STATE="New Jersey"

#################################         END       #############################
