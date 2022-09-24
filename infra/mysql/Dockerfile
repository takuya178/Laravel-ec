FROM mysql/mysql-server:8.0

ENV MYSQL_DATABASE=laravel-ecsite \
  MYSQL_USER=takuya \
  MYSQL_PASSWORD=taku178 \
  MYSQL_ROOT_PASSWORD=taku178 \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf