FROM centos:centos7

RUN yum install -y vim initscripts git sed less make
RUN yum install -y gcc gcc-c++
RUN yum install -y flex bison readline-devel zlib-devel xerces-c-devel
RUN yum install -y epel-release
RUN yum install -y cmake3 

RUN  \
  echo "export CXX=/usr/bin/g++" >> /root/.bashrc && \
  echo "alias cmake=cmake" >> /root/.bashrc
