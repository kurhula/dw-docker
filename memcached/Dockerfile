# Version 1.0
FROM ubuntu
MAINTAINER Musa Baloyi <musabaloyi@aims.ac.za>
WORKDIR /home
RUN sudo apt-get update
RUN sudo apt-get install -y memcached
EXPOSE 11211
CMD ["-m", "128"]
USER daemon
ENTRYPOINT memcached
