FROM alpine

RUN apk update
RUN apk add mysql-client

WORKDIR /opt

COPY import.sh .
COPY mydatabase.sql .

CMD ["sh", "import.sh"]
                       
