FROM python:3.7.5-alpine3.10

RUN apk update \
    && apk add --upgrade --no-cache \
      openjdk11-jre \
      g++ \
    && pip install pipenv \
    && rm -r /root/.cache

ENV JAVA_HOME="/usr/lib/jvm/java-11-openjdk"
ENV LD_LIBRARY_PATH=/usr/lib/jvm/java-11-openjdk/jre/lib/server

