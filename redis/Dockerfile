FROM ubuntu
RUN apt-get update
RUN apt-get -y install git
RUN apt-get install make
RUN apt-get -y install gcc
RUN apt-get -y install pkg-config
RUN apt-get -y build-essential

## for tcl
ENV TZ=Asia/Kolkata \
    DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
    apt-get install tzdata
RUN apt-get -y install tcl

RUN git clone https://github.com/redis/redis.git 


