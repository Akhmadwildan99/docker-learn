########################################################
# Dockerfile to demonstrate the behaviour of CMD
########################################################
# Base image is Ubuntu
FROM ubuntu:14.04
MAINTAINER Dr. Wildan <wildan@bti.id>
# Install apache2 package
RUN apt-get update && \
apt-get install -y apache2 && \
apt-get clean
# Set command for CMD
CMD ["echo", "Dockerfile CMD demo by wildan"]