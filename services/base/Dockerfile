FROM ruby:2.7-alpine

RUN apk add --no-cache build-base gcc bash cmake git
RUN apk add --update supervisor && rm  -rf /tmp/* /var/cache/apk/*

RUN mkdir -p ./src

RUN gem install jekyll


WORKDIR ./src