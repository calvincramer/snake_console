### Using alpine image

`docker pull ubuntu`

### Create container

`docker create -it --name=linux ubuntu:__tag__ /bin/bash`

Note doesn't bind folder

### Create container with mounted folder

`docker run --name=linux -it -v //c/Users/CalvinLaptop/CalvinLaptop_Files/snake:/snake ubuntu:v2 /bin/bash`

### Start and attach

```
docker start linux
docker attach linux
```

### Commit changes

`docker commit __containername__ __imagename:tag__`
