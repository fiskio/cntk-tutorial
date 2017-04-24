# CNTK - Handwriting Recognition Tutorial

Use CNTK to train a feed forward network that recognises letters and numbers!

## Requirements:
`docker`  the best way to install it depends on your OS, try [here](https://www.docker.com/community-edition).  
`docker-compose`  *pip install docker-compose*  

For **GPU** also:  
`nvidia-docker`  the best way to install it depends on your OS, try [here](https://github.com/NVIDIA/nvidia-docker/wiki/Installation).  
`nvidia-docker-compose`  *pip install nvidia-docker-compose*  

## Setup
To build the docker image run:  
`docker build --rm -t cntk-tutorial -f ./Dockerfile-CPU .`  

...or for **GPU** run:  
`docker build --rm -t cntk-tutorial -f ./Dockerfile-GPU .`  

## Run
`docker-compose up`  
...or for **GPU** run:  
`nvidia-docker-compose up`

This will start a *Jupyter* server, on port 8888 and a *Tensorboard* web ui on port 6006.

The official CNTK python documentation is [here](https://www.cntk.ai/pythondocs/).

Let's have fun!
