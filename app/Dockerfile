FROM ruby:latest

WORKDIR /home/playground

RUN gem install fluentd && \
  apt update && \
  apt-get install -y curl vim git
