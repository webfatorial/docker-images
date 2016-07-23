FROM webfatorial/node

MAINTAINER webfatorial <webfatorial@webfatorial.com>

RUN apt-get -y install sudo

RUN sudo npm install -g yo
RUN sudo npm install -g generator-trails

RUN useradd -ms /bin/bash docker

USER docker

EXPOSE 35729
