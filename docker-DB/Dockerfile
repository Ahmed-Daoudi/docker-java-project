FROM mysql:5.7.25
LABEL "Project"="java-application"
LABEL "Author"="Ahmed"


ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="mysql-DB" 

ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql