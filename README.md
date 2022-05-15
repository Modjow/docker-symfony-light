# docker-symfony-light

Simple docker configuration with :
- Nginx (1.21-alpine)
- PHP (8.1-alpine)
- MariaDB (10.7.3)
- Adminer (latest)
- Symfony (6.0.8)

Build:
```shell
docker-compose build --pull --no-cache
```

Run in developpment environnement:

```shell
docker-compose up --build -d
```

Run in production environnement :

```shell
docker-compose -f docker-compose.yml -f docker-compose-production.yml up
```
