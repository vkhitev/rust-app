# rust-app

## Useful commands

### Start Postgres

```bash
docker-compose up -d
```

### Show logs

```bash
docker logs -f rust-app-postgres
```

### Run psql

```bash
docker exec -it rust-app-postgres psql -U postgres
```

### Create database

```bash
docker exec -it rust-app-postgres psql -U postgres -c "create database my_database"
```
