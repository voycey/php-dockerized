# PHP Dockerized

> Dockerized PHP development stack: Nginx, MySQL & PHP-FPM

[![Build Status](https://travis-ci.org/voycey/php-dockerized.svg)](https://travis-ci.org/voycey/php-dockerized)

This is a slimmed down version of the forked repo, I have a custom one I have built using Phusion Baseimage but as a quick and trusted delivery to a client I need one built from official images.

## What's inside

* [Nginx](http://nginx.org/)
* [MySQL](http://www.mysql.com/)
* [PHP-FPM](http://php-fpm.org/)

## Requirements

* [Docker Engine](https://docs.docker.com/installation/)
* [Docker Compose](https://docs.docker.com/compose/)
* [Docker Machine](https://docs.docker.com/machine/) (Mac and Windows only)

## Running

Set up a Docker Machine and then run:

```sh
$ docker-compose up
```

That's it! You can now access your configured sites via the IP address of the Docker Machine or locally if you're running a Linux flavour and using Docker natively.

## License

Copyright &copy; 2014-2015 [Kasper Kronborg Isager](http://github.com/kasperisager). Licensed under the terms of the [MIT license](LICENSE.md).
