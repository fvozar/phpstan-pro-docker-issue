To replicate the issue with phpstan pro inside a docker container run the following commands:

```bash
docker-compose up
docker-compose exec php composer install
docker-compose exec php vendor/bin/phpstan --pro
```
