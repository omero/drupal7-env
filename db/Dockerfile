FROM mysql

ENV MYSQL_ROOT_PASSWORD root
ENV MYSQL_DATABASE drupal
ENV MYSQL_USER drupal
ENV MYSQL_PASSWORD drupal

ONBUILD RUN mysql -uroot -proot -e "create database foo;"
ONBUILD RUN mysql -uroot -proot -e "create database bar;"
