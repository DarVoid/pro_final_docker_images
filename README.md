# Final Project - Docker Images
### To build images from these docker files:
```sh
1- change folder to desired package you want to try
2- docker build -t <nameYouDesireForTheDockerContainer> .
3- docker run -p <port>:8888 <nameYouDesireForTheDockerContainer>:latest
  
```
### To use Jupyter Notebook for time-matters:
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
Introduce the ip on a web broswer with the respective port.

Further information about the notebook in [here](https://hub.docker.com/r/liaad/time-matters).
### To use Jupyter Notebook for py_heideltime:

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

Finally, introduce the ip on a web broswer with the respective port.


Further information about the notebook in [here](https://hub.docker.com/r/liaad/py_heideltime).
