# PHP et MySQL avec Docker

## Prérequis

- [Docker](https://docs.docker.com/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Lancer le projet

```bash
docker-compose up
```

## Env file:

Need to set your credentials

### MongoDB Environment
MONGO_INITDB_ROOT_USERNAME=
MONGO_INITDB_ROOT_PASSWORD=
MONGO_EXPRESS_USERNAME=
MONGO_EXPRESS_PASSWORD=

### MySql Environment
MYSQL_ROOT_PASSWORD=
MYSQL_DATABASE= 
MYSQL_USER= 
MYSQL_PASSWORD= 

## Accessing MongoDB with mongo-express

You have to access by pointing your browser to the url `http:\\localhost:8081`. You will be prompted to enter a login and a password : you type the value defined for `MONGO_EXPRESS_USERNAME` and `MONGO_EXPRESS_PASSWORD` in the `.env` file.
