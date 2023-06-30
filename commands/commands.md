### Docker compose up
```cmd
docker compose up -d 
:: d is for detached
```

### Docker compose run
```cmd
docker compose run service-name
docker compose run web node -v
:: you can run a specific container using the docker compose run
:: or maybe even just running a command inside the container directly
```

### Docker compose build
```cmd
docker compose build
docker compose build service-name
:: does not execute the container, just builds the images
```
