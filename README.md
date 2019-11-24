# Docker Server

### Requirements
- Docker Compose >= 3.0
- Docker >= 1.17.0

### Software
- NGINX stable as reverse proxy, static file server and cache
- Apache 2.4 as dynamic web server, php-fpm proxy, htaccess config loading
- PHP 5.6 / 7.0 / 7.1 / 7.2 / 7.3 as FPM with xdebug, memcached, opcache and APCu
- MySQL 5.7 as database server
- NPM LTS (optional) for building frontend assets
- Mailhog for mail catching and testing

### Usage
- Setup Vars in .env
- Change versions in .env
- Start server with `docker-compose up -d`
- Stop server with `docker-compose down`
