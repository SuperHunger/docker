FROM mysql
MAINTAINER zehui "346272043@qq.com"
RUN sed '33 acharacter-set-server=utf8' -i /etc/mysql/my.cnf && \
	sed '22 adefault-character-set=utf8' -i /etc/mysql/myc.cnf
	
EXPOSE 3306
CMD ["mysqld"]