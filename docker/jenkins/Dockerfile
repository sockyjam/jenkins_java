FROM jenkins/jenkins:lts
MAINTAINER SockyJam <sockyjam@126.com>


# if we want to install via apt
USER root
RUN apt-get update 
RUN apt-get install -y rsync


# drop back to the regular jenkins user - good practice
USER jenkins
