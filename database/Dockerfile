FROM mysql:8

# set env variable for root user
ENV MYSQL_ROOT_PASSWORD=password

# copy data sql file to the docker entry point
COPY ./data.sql /docker-entrypoint-initdb.d/