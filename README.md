# Final Project - Docker Images
### To use jupyter notebook for time-matters:
Pull time-matters image from Docker Hub: 
```sh
$ docker pull liaad/time-matters
```
Verify if the docker image is in:
```sh
$ docker images
```
Run the container
```sh
$ docker run -p 9999:8888 –user root liaad/time-matters
```
Discover the IP address:
```sh
$ docker-machine ip
```
Finally, introduce the ip on a web broswer with the respective port.

Further information about the notebook in [here](https://hub.docker.com/r/liaad/time-matters).
### To use jupyter notebook for py_heideltime:
Pull py_heideltime from Docker Hub

Pull time-matters image from Docker Hub: 
```sh
$ docker pull liaad/py_heideltime
```
Verify if the docker image is in:
```sh
$ docker images
```
Run the container
```sh
$ docker run -p 9998:8888 –user root liaad/py_heideltime
```
Discover the IP address:
```sh
$ docker-machine ip
```
Finally, introduce the ip on a web broswer with the respective port.


Further information about the notebook in [here](https://hub.docker.com/r/liaad/py_heideltime).
