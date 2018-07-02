# deep-learning-docker
Need to test any algorithm in any particular deep learning framework without installing and messing out your system wrt versions etc??
Use the following docker containers for quick prototyping and testing.. 

This repository contains links to docker containers for all the deep learning frameworks.
Each framework is built on top of fresh ubuntu system. You just need to pull it and use it. 

## Pre-requisites
1. Ubuntu 16.04
2. Docker installation on ubuntu..

## Caffe2
Here is the link for [Caffe2 CPU version](https://hub.docker.com/r/lcskrishna/caffe2-docker/) docker file.

To use it, follow the below instructions:

```
% sudo docker pull lcskrishna/caffe2-docker
% sudo docker run -it -v /home/:/root/hostmachine --network host lcskrishna/caffe2-docker
% cd 
```

This maps home directory of your ubuntu system with hostmachine folder.


## Tensorflow
Here is the link for [Tensorflow CPU Version](https://hub.docker.com/r/lcskrishna/tensorflow-docker/) docker file.

To use it, follow the below instructions:

```
% sudo docker pull lcskrishna/tensorflow-docker
% sudo docker run -it -v /home/:/root/hostmachine --network host lcskrishna/tensorflow-docker
```

This maps the home directory of your ubuntu system with the hostmachine folder in the docker directory.
