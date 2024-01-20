FROM ubuntu:22.04

RUN apt update
RUN apt install -y git
RUN apt install -y libyaml-dev
RUN apt install -y rbenv
RUN git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
RUN rbenv install 3.0.2
RUN apt install -y ruby-dev
RUN gem install bundler -v 2.5.4
RUN gem install rails -v 7.0.0

