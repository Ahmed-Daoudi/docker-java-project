FROM ngnix
LABEL "Project"="java-application"
LABEL "Author"="Ahmed"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY java-app.conf /etc/nginx/conf.d/java-app.conf

