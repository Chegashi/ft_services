FROM debian:buster
ARG TAG="mariadb"
COPY conf  /
COPY tools /
EXPOSE 443
RUN ["apt-get", "-y", "update"]
RUN ["apt-get", "-y", "upgrade"]
# RUN ["apt-get", "install" , "-y", "mariadb-server", "mariadb-client"]

