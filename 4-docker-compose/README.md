## Run docker container
$ docker build -t myubuntu:1.0 .

$ docker container list --all

$ docker image list

$ docker run -it --name mycontainer myubuntu:1.0

## Clean up
$ docker ps

$ docker stop mycontainer

$ docker rm mycontainer