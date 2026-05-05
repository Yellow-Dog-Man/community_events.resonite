Docker Compose 2.24.4 and later plz

`docker compose --env-file .env -f stacks/prod/ydms.docker-compose.yml --profile "*" up`

`docker exec -it prod-database-1 psql -U events -d events` for a db shell.


For web updates(silly html challenges): `docker compose --env-file .env -f stacks/prod/ydms.docker-compose.yml --profile "*" up --force-recreate --build -d web_client` may be faster.

