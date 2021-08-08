## Run docker container
$ docker run --name myserver -p 90:80 nginx
#### http://localhost:90/

## Interactive pseudo-terminal
$ docker exec -it myserver /bin/bash

$ apt-get update

$ apt-get install nano

### Find nginx index.html and make some modification
$ find / -name index.html

$ cd /usr/share/nginx/html

$ nano index.html

$ cat index.html

## Clean up
$ docker ps

$ docker stop myserver

$ docker rm myserver