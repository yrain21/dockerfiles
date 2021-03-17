FROM mysql:5.7

COPY my.cnf /etc/mysql/conf.d/my.cnf

RUN chmod 0777 /etc/mysql/conf.d/my.cnf

EXPOSE 3306

CMD ["entrypoint.sh"]