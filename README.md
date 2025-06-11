# 接口测试
````
http :8888/catalog-service/default
http :8888/catalog-service/prod
````

# Docker命令
````
docker run -d \
    --name config-service \
    -p 8888:8888 \
    config-service
    
docker rm -f config-service
````