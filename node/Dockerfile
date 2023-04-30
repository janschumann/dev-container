FROM node:18 as deps
WORKDIR /app

RUN curl -o helm.tgz https://get.helm.sh/helm-v3.11.3-linux-amd64.tar.gz \
    && tar -zxvf helm.tgz \
    && mv linux-amd64/helm /usr/local/bin/helm \
    && rm -Rf linux-amd64 helm.tgz

