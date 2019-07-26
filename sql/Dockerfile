FROM mysql:5.7

ENV PATH = /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
ENV GOSU_VERSION = 1.7
ENV MYSQL_MAJOR = 5.7
ENV MYSQL_VERSION = 5.7.27-1debian9
ENV MYSQL_ALLOW_EMPTY_PASSWORD =true

COPY init_db.sh /docker-entrypoint-initdb.d/init_db.sh

EXPOSE  3306


