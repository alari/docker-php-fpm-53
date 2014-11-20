docker-php-fpm-53
=================

Docker image for obsolete php-fpm 5.3

docker run -d -v /var/www:/srv/http -v /var/run/mysqld.sock:/tmp/mysqld.sock -p 9000:9000 --name php-fpm alari/docker-php-fpm-53:latest
