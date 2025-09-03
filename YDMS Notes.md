Docker Compose 2.24.4 and later plz

`docker compose --env-file .env -f stacks/prod/ydms.docker-compose.yml --profile "*" up`

Occasionally, you'll need to force a fresh build which will be:

`docker compose --env-file .env -f stacks/prod/ydms.docker-compose.yml --profile "*" up --force-recreate --build`