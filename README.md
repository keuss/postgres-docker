# postgres-docker

PostgreSQL and Docker test with docker-compose and :

 - https://github.com/docker-library/docs/blob/master/postgres/README.md
 - https://hub.docker.com/r/dpage/pgadmin4/
 
## Run

 - `docker-compose up -d` (-d option to put it into detach mode)
 - See containers with `docker-compose ps`
 - See volumes with `docker volume ls`
 - Introspect with `docker container inspect postgres_container`
 - Logs `docker-compose logs -f`
 - Stop with `docker-compose up`
 - Remove volumes (to chage configuration, ...) `docker volume rm 01-postgres_pgadmindata 01-postgres_dbdata`
 - list all containers : `docker container list -a`, all images : `docker image ls`
 
Test with pgAdmin4

 - http://localhost:8080/ (guillaume.gallois@gmail.com / secret). Must create a server first and connection with hostname `db` (see services in yml)
 
## Links

 - https://linuxhint.com/postgresql_docker/ and [here](https://phoenixnap.com/kb/deploy-postgresql-on-docker) or [here](https://github.com/khezen/compose-postgres/blob/master/docker-compose.yml)
 - [Install docker on CentOS 8](https://github.com/keuss/docker-on-centos8)
