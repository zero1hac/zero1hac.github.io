---
layout: post
title: A Full-fledged docker image for Deep Learning
---

If you are stuck at installing deep learning toolkits or don't want to waste your time installing it by reading big manual installation guides, this is the right place you are looking at. I'll introduce you the easiest way out of this trouble by using [Docker](https://www.docker.com/).

## Do I really need this Docker image?
Installing different Deep learning frameworks to function correctly together is a difficult task because of the dependencies. Also, in the current scenario of Deep Learning Research, it is almost impossible to rely on just one framework. If you are a Deep learning artist then you really need this docker image unless you want to install every framework manually. Using the framework through Docker container is not different than using it in your system's environment and has no performance impact during runtime.
Since, Docker containers are persistent so there is no chance of messing up the configuration of the image. You can always kill the container and spin up a fresh container from the same image. So, this container is must have for your Deep learning projects.

## Specifications

 - [Ubuntu 14.04](https://www.ubuntu.com/download)
 - [Tensorflow](https://www.tensorflow.org/)
 - [Caffe](http://caffe.berkeleyvision.org/)
 - [Theano](https://github.com/Theano/Theano)
 - [Keras](https://keras.io/)
 - [Lasagne](https://github.com/Lasagne/Lasagne)
 - [Torch](http://torch.ch/)
 - [Jupyter notebook](http://jupyter.org/)
 - [numpy](http://www.numpy.org/), [scipy](https://www.scipy.org/), [pandas](http://pandas.pydata.org/), [scikit-learn](http://scikit-learn.org/), [matplotlib](http://scikit-learn.org/)
 - [OpenCV](http://opencv.org/)

## Setup

#### Prerequisites
 1. Install Docker in your system using the installation guide [here](https://docs.docker.com/engine/installation/)

