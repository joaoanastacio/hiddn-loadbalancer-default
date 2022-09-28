FROM --platform=linux/amd64 kong:2.7-centos

LABEL DOCKERFILE_DESCRIPTION = "CentOS 7 + Kong 2.7 using Kong OIDC plugin (Luarocks)"

USER root

RUN yum install sudo -y git unzip && yum clean all

RUN luarocks install kong-oidc