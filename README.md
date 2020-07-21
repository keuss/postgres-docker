# postgres-docker


PostgreSQL and Docker test with docker-compose and :

 - https://github.com/docker-library/docs/blob/master/postgres/README.md
 - https://hub.docker.com/r/dpage/pgadmin4/
 
Run

 - `docker-compose up -d` (-d option to put it into detach mode)
 - See containairs with `docker-compose ps`
 - See volumes with `docker volume ls`
 - Introspect with `docker container inspect postgres_container`
 - Logs `docker-compose logs -f`
 - Stop with `docker-compose up`
 
Test with pgAdmin4

 - http://localhost:8080/ (guillaume.gallois@gmail.com / secret). Must create a server first and connection with hostname `db` (see services in yml)
 

Links

 - https://linuxhint.com/postgresql_docker/ and [here](https://phoenixnap.com/kb/deploy-postgresql-on-docker)
