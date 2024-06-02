FROM debian
RUN apt-get -y update
# Update package lists and install required packages
RUN apt-get -y install nmap ftp john iproute2
RUN apt-get update && \
    apt-get install -y iproute2 proftpd-basic && \
    apt-get clean
