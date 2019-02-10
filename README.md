## docker environment

## Application Structure
##### |- docker-composer.yml `docker compose config`
##### |
##### |- conf.d `docker config file`
##### |-- apache `apache config file`
##### |--- *.conf
##### |
##### |- mariadb `mariadb image`
##### |--data `database files`
##### |--my.cnf `config mariadb`
##### |--Dockerfile
##### |
##### |- mongodb `mongodb image`
##### |--data `database files`
##### |-- Dockerfile
##### |
##### |- services
##### |-- id `sso server services`
##### |--- Dockerfile
##### |--- ...
##### |
##### |-- gateway `api gateway services`
##### |--- Dockerfile
##### |--- ...
##### |
##### |-- *resources* `other resources services`
##### |--- Dockerfile
##### |--- ...

## clone resource to resource forders
