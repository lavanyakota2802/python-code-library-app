FROM mysql:5.7.44
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_USER=root
COPY ./database/database.sql /docker-entrypoint-initdb.d/
