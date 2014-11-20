Docker: php-fpm 5.3
=================

Docker image for obsolete php-fpm 5.3

Usage:

`docker run -d -v /var/www:/srv/http -v /var/run/mysqld.sock:/tmp/mysqld.sock -p 9000:9000 alari/php-fpm-53:latest`

- Bind your script sources to `/srv/http` or subfolders.
- Expose port 9000 to your server (either dockerised, like `dockerfile/nginx`, or not).
