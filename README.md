# Setup local env

- Install Docker Desktop https://docs.docker.com/get-docker/
- Install Git and setup access token to repository
- Clone repository in your folder
- Run in console `docker network create palumni-external`
- Run in console `docker-compose up -d`
- Copy .env-dev to .env
- Create new DB (and configure in .env)
- Open docker webserver container in terminal, run bash
- Run `chmod 777 -R storage`
- Run `chmod 777 -R bootstrap/cache`
- Add `127.0.0.1 palumni.local` to your hosts file 
- Run `/start.sh`
- Run `composer install`
- Run `npm -i`
- Run `php artisan migrate`
