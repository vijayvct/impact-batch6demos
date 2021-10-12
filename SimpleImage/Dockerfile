#use an existing image as a base image 
FROM ubuntu

LABEL "maintainer" "Vijay Vishwakarma"

#download and install dependecies 
RUN apt-get update
RUN apt install apache2 -y

#expose port 80
EXPOSE 80