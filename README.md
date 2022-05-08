## Configuration

```sh
cp .env.example .env
docker-compose up -d
```

The following endpoints are now exposed:

- `localhost:5432`: Postgres DB (latest)
- `http://localhost:8081`: Postgres Web admin
- `localhost:1883`: Eclipse Mosquitto (v1.6.15)
