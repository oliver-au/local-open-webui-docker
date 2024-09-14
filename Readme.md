## Create open-webui volume before starting the service for the first time:
```
docker volume create open-webui
```

## Start the service:
```
docker-compose up -d
```

## Start the service with pulling the latest images:
```
docker-compose up -d --pull always
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

## After the first start, you can access the web interface at `http://localhost:3100/auth` to create an admin account.

