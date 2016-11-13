FROM oraclelinux:latest

RUN yum -y update \
    && yum -y install ipvsadm curl \
    && yum clean all

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT /entrypoint.sh
