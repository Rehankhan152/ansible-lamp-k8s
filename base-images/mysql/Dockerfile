FROM ubuntu:22.04
RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y mysql-server && \
    mkdir -p /var/lib/mysql && chmod 755 /var/lib/mysql
EXPOSE 3306
CMD ["mysqld_safe"]