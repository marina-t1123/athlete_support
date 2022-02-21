FROM mysql:8.0

ENV MYSQL_DATABASE=athlete_support \
  MYSQL_USER=marina \
  MYSQL_PASSWORD=dnll1031 \
  MYSQL_ROOT_PASSWORD=root \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf