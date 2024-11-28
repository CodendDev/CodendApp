# CodendApp

This is not production ready. You have to configure FusionAuth and PostgreSQL
secrets by yourself. You can also use your own SSL certificate customizing nginx
ssl volumes in docker-compose.

## Showcase video

[CodendApp Showcase Video on YouTube](https://www.youtube.com/watch?v=7UjuAdRjDh0)

## Run application

### using Docker Hub images

```bash
git clone https://github.com/CodendDev/CodendApp codendapp
cd codendapp
docker compose up
```

### build from source

```bash
git clone https://github.com/CodendDev/CodendApp codendapp --recurse-submodules
cd codendapp
docker compose up --build
```

## Access the application

Visit https://127.0.0.1:8080 in your browser.

You can login using any default user account.

User emails:

```
fred@codend.com
```

```
barney@codend.com
```

Default password:

```
password
```

You can also access:

- API using SwaggerUI https://127.0.0.1:8081/swagger/
- FusionAuth https://127.0.0.1:9011 using default FusionAuth credentails
```
admin@codend.com
```
```
password
```
