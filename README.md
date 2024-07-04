# Harbor deployment

Para el desployment de harbor sobre docker 

## Prerequisito
 
* Instalar docker
Hay varios metodos pero el que mas me gusta es :
```
 $ curl -fsSL https://get.docker.com -o install-docker.sh
 $ chmod 700 install-docker.sh
 $ ./install-docker.sh
 $ 
```

* Instalar docker compose
Para ello usare
```
sudo curl -L "https://github.com/docker/compose/releases/download/v2.81.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

check version
docker-compose --version

- 
