############################################################ 
# Dockerfile to build Ubuntu image for aliyun ecs
# Based on Ubuntu:14.04
############################################################

FROM ubuntu:14.04
MAINTAINER Zhang Xinye <xinye@zhijin.com>

# Replace aliyun repository URL to the default sources
RUN sed -i 's/archive.ubuntu.com/mirrors.aliyun.com/' /etc/apt/sources.list

# Update the repository and patch system
RUN apt-get update -y && \
    apt-get install bash libc6 libc-bin openssl wget ntp -y

# Replace aliyun ntp server
ADD ntp.conf /etc/ntp.conf