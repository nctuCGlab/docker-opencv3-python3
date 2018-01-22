# docker-opencv3-python3 #

## Build up

```
git clone https://github.com/nctuCGlab/docker-opencv3-python3.git
cd docker-opencv3-python3
docker build -t opencv3-python3 .
```

## Create container

check images
```
docker images
```

simple:
```
docker run -itd <image_name>
```

with name:
```
docker run -itd --name cv3 <image_name>
```

mount directory:
```
docker run -itd -v <host_directory>:/root <image_name>
```

more:
[docker run](https://docs.docker.com/engine/reference/commandline/run)

## Get into container
check container live
```
docker ps -a
```

enter with bash
```
docker exec -it <container_name> bash
```
