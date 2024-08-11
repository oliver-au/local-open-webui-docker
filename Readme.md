## Start the service:
```
docker-compose --env-file ./.env up -d
```

## Stop the Services
```
docker-compose down
```

## Remove All Data (Volumes)
```
docker-compose down --volumes
```

## Add OpenAI API Key in .env from .env-local