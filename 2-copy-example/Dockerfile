###   2-Example  -    Dockerfile - Copy files from the HOST 
#################################         START     ################ ############

## Here the  base image is alpine
FROM alpine:3.12  
RUN apk add  curl
RUN apk add nano

### create a directory using mkdir linuxcommand ##  _some_name_of_the_directory
RUN mkdir some-test-dir

### if we wanted to copy files from host computer from PWD ##########
COPY ./ ./some-test-dir

#################################         END       #############################
