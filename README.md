# CodendApp

## Run application

### using Docker Hub images

```bash
git clone https://github.com/CodendDev/CodendApp codendapp
cd codendapp
docker compose -f docker-compose.pull.yml up
```

### build from source

```bash
git clone https://github.com/CodendDev/CodendApp codendapp --recurse-submodules
cd codendapp
docker compose -f docker-compose.build.yml up
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
* API 
    * https://127.0.0.1:8080/codend/api/
    * using SwaggerUI https://127.0.0.1:8080/codend/api/swagger
* FusionAuth
    * https://127.0.0.1:9011