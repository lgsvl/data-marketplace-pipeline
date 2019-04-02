FROM zlabjp/kubernetes-resource

MAINTAINER Mohamed Mohamed <mohamedmohamedphd@gmail.com>

ARG KUBERNETES_VERSION=
RUN mkdir -p /opt/resource
COPY assets/* /opt/resource/
RUN mkdir /root/.aws/
COPY credentials /root/.aws/
RUN mkdir /root/.ssh/

