FROM mysql

ENV MYSQL_ROOT_HOST='%'
ENV MYSQL_ROOT_USER='root'
ENV MYSQL_ROOT_PASSWORD='7htdv3eh5t'
ENV MYSQL_DATABASE='mysql'

EXPOSE 3306

#Below command required for some django app runnings on some OS e.g. alpine
CMD ["--default-authentication-plugin=mysql_native_password"]