FROM ubuntu
ENV DEBIAN_FRONTEND noninteractive

RUN apt-get install --assume-yes -qq memcached telnet
USER daemon

EXPOSE 11211

CMD ["memcached", "-u", "root"]