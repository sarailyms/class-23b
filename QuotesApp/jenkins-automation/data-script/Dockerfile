FROM alpine
RUN apk update && apk upgrade
RUN apk add mysql-client
WORKDIR /opt
COPY . .
RUN chmod +x import.sh
CMD ["/bin/sh", "/opt/import.sh"]