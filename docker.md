#### dockerizing
```
docker build -t taixingbi/react-hello .
docker push taixingbi/react-hello

docker run --publish 3000:3000 taixingbi/react-hello
```

#### basic
```
docker images
docker ps -a
```

#### delete
```
docker stop $(docker ps -aq)    
docker rm $(docker ps -aq)    
docker rmi $(docker images -q) 
```



