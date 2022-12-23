FROM mysql:5.7.30

COPY ./dump/dump.sql /tmp

CMD [ "mysqld", "--init-file=/tmp/dump.sql" ]