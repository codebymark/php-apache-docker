# Docker Compose Boilerplate Environment
A boilerplate docker environment, probably pretty handy to those looking to start using containers. 
PHP and Apache are in separate containers to make it easy to change versions as required. 
- Apache 2.4
- PHP/PHP-FPM 7.1

## Setup
```$php
docker-compose up -d 
```

## General Usage Info
- Working directory ./src
- Config for apache and php is in ./config
- Port 80 is open 

## Licence
None
