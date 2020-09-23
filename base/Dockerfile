# Using official ubuntu image as a parent image
FROM ubuntu:latest

ARG DEBIAN_FRONTEND=noninteractive

# Update aptitude with new repo
RUN apt-get update

# Install software 
RUN apt-get install -y git-all

RUN apt-get install -y nodejs
RUN apt-get install -y npm
RUN apt-get install -y yarn
