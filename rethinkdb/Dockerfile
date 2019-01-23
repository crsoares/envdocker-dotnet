FROM rethinkdb:latest

LABEL maintainer="Cristian Mello <cristianc.mello@gmail.com>"

RUN apt-get update && \
    apt-get -y install nano && \
    apt-get -y install net-tools

VOLUME /data/rethinkdb_data

RUN cp /etc/rethinkdb/default.conf.sample /etc/rethinkdb/instances.d/instance1.conf

CMD ["rethinkdb", "--bind", "all"]

EXPOSE 8080
