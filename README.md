docker-swoole
=============

Collection of different swoole-docker solution for you reference.

## [betashepherd/] (./betashepherd/)

from betashepherd/docker-swoole

## [deprecated] [alpine_php7_runtime_with_swoole/](./auto_alpine_php7_runtime_with_swoole/)

php7-runtime +swoole based on alpine-edge.  Build from PECL, and some patches needed to finish compile.
As building from source directly is tested (see below), so this folder is deprected while kept only for reference.

## [alpine_php7_runtime_with_swoole_latest/](./auto_alpine_php7_runtime_with_swoole_latest/)

php7(latest)-runtime +swoole based on alpine-edge, which build from [swoole-src](https://github.com/swoole/swoole-src/) directly.

## [ php docker app server ](./auto_cmp_php_docker_server/)

Base on auto_alpine_php7_runtime_with_swoole_latest, more latest7 extension, ready for app server

## LINKS

* Install Docker*
[Visit Docker-Doc](https://docs.docker.com/)

* app server example (swoole+phpfpm)
(https://github.com/cmptech/cmp_app_server)
