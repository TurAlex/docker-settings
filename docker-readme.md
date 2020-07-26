## Add to .env

APP_NAME=settings  
DOCKER_NETWORK=192.168.110.0/24  
DOCKER_BRIDGE=192.168.110.1  

REDIS_CLIENT=predis  
REDIS_HOST=127.0.0.1  
REDIS_PASSWORD=root  
REDIS_PORT=6379  
REDIS_DB=0  
REDIS_CASHE_DB=1

## Add to .gitignore
/docker/storage/db/mysql  
/docker/storage/logs



