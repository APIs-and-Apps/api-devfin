# api-devfin

API for devfin project based on json-server.

## Running with docker

```
docker run -d -p 80:80 -v "$PWD"/db.json:/data/db.json clue/json-server
```

```
Browse to http://localhost
```

## Running without docker
```
json-server --watch db.json
```

```
Browse to http://localhost:3000
```