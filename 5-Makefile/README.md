## Run docker container
$ docker build -t devenv .

$ docker container list --all

$ docker image list

$ docker run --name myenv -it -v ~/Documents/test:/projects/myapp devenv

## Compile main.c
$ make

## Clean up
$ docker ps

$ docker stop mycontainer

$ docker rm mycontainer
