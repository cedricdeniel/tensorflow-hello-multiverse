```shell
# Build docker image
$ docker build . --tag=tf-hello-multiverse

# Run image on a non-Windows host
$ docker run -it -p 8888:8888 tf-hello-multiverse
# Or on Windows host
$ winpty docker run -it -p 8888:8888 tf-hello-multiverse
```
