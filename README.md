````
docker run -d \
    --name config-service \
    -p 8888:8888 \
    config-service
    
docker rm -f config-service
    
http :8888/catalog-service/default
http :8888/catalog-service/prod
````