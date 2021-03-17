FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD=123456@p

COPY my.cnf /etc/mysql/my.cnf

RUN chmod 644 /etc/mysql/my.cnf

ENTRYPOINT ["docker-entrypoint.sh"]

EXPOSE 3306

CMD ["mysqld"]
