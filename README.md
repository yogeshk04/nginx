# nginx
Understanding Nginx

## Commands
```
docker-compose up -d
docker build -t webserver .
docker run -it --rm -d -p 8080:80 --name web webserver
```

## Nginx commands
### Use be used in Attached shell of a container 
```
ps -C nginx -f 
nginx -s reload
ps -C nginx -f 
```