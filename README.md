# LoRaTrust Prototype Backend

## Configuration with Docker
1. initialize docker

### Dev
1. Change docker-compose.yml, change the dockerfile to ```dockerfile: Dockerfile.dev```
2. ```docker-compose build```
3. ```docker-compose up```

#### Production
1. Change docker-compose.yml, change the dockerfile to ```dockerfile: Dockerfile```
2. ```docker-compose build```
3. ```docker-compose up```

### Withoud Docker-Compose

1. ```docker build -t loratrustprototypebackend .```
2. ```docker run -p 8000:8000 loratrustprototypebackend```


## Configuration without Docker
1. Run the code -> ```npm run dev```
2. To see al the possible path see: http://localhost:8000/docs/ 


## Used Technology

- Node
- Express
- Typescript
- nodemon (automate build typescript ot javascript)
- morgan (log requests command line)
- swagger integration (documentation)
