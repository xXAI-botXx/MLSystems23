# Assignment 2: Docker

**Note:** for this assignment we use the bwLehrPool infrastructure. Boot the lab PC and start the ***XFCE Base Linux***.

## Links
* [Docker Reference](https://docs.docker.com/reference/)
* [Docker Hub](https://hub.docker.com/)
* [NVIDIA NGC](https://catalog.ngc.nvidia.com/containers)

## Basics
* Start a terminal and check the docker installation:
```
docker --version
```

* Check for running containers:
```
docker ps
```

* List localy available *images*:
```
docker images
```


### Tasks
#### Run your first container:
```
docker run hello-world
```
* Check local *images* again... what happend? 

#### Get a *Jupyter* and *Scikit-Learn* container running
* find a suitable image on *Docker Hub*
* pull the image
* start the container and open ```localhost:8888``` in your browser (Port my vary depending on the image you use)
* open a second terminal and check the state of running containers ```docker ps``` -> get the current container *ID*
* stop the container
* delete the image from the system

## Storage
Everything we store/save inside the container will be lost when the container terminates. Hence we want to mount persitent storage.

* [Bind-mount Docu](https://docs.docker.com/storage/bind-mounts/)

### Tasks
* create a folder in you home and mount it into the container *jupyter* container at start time. 

## Network

### Tasks


## Changing Images

### Tasks


## Building Images

### Tasks


## Publishing Images


### Tasks

