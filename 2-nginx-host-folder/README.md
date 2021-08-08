## Run docker container
$ docker run --name myserver2 -d -p 8001:80 -v ~/Documents/test:/usr/share/nginx/html nginx
#### http://localhost:8001/

## Clean up
$ docker ps

$ docker stop myserver2

$ docker rm myserver2