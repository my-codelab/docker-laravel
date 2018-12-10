# docker-laravel
Sample of docker-compose with laravel, nginx, php-fpm
## Target
run like `php artisan serve` but from container docker
## Prerequisite
```
docker
docker-compose
docker-machine
```
## Variable
- `docker-machine ip` is your docker machine ipd
## Usage
### Laravel Step
- Execute your command/bash to laravel dir
- `composer install`
### Docker Step
- At base directory/root execute command `docker-compose up` to run container.
- Then browse or curl url `http://{docker-machine-ip}` and output is homepage of laravel demo;
- `docker-compose down` to shutdown docker container
## Todo
- Database