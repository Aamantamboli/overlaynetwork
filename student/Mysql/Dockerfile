FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=1234

COPY student-rds-table.sql /docker-entrypoint-initdb.d/

EXPOSE 3306

CMD [ "mysqld" ]