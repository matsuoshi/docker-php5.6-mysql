# docker-php5.6-mysql

- php 5.6
- mysql 5.7
- apache

$ docker-compose up

## web

http://127.0.0.1:8080/

## local to mysql
$ mysql -h 127.0.0.1 -P 33306 -u php56 -p

## web to mysql
mysql://php56:password@db:3306/php56-db
