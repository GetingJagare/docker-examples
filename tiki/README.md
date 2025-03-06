## Create the certificates directory 
```bash
mkdir certs
```

## Execute this command
```bash
openssl req -x509 -sha256 -nodes -newkey rsa:2048 -days 365 -keyout certs/ontoloo.key -out certs/ontoloo.crt
```

## Run Docker Compose
```bash
docker compose up
```
