FROM alpine

RUN apk update && apk add python3

RUN apk add py3-pip

RUN pip3 install django

RUN pip3 install pymysql

#RUN pip3 install packaging

#RUN pip3 install cryptography

WORKDIR mysqldjango

COPY . .

EXPOSE 8000

CMD ["./django_migrate_and_runserver.sh"]

