# ESPnet: end-to-end speech processing toolkit

Docker images from ESPnet https://github.com/espnet/espnet [![Build Status](https://travis-ci.org/espnet/espnet.svg?branch=master)](https://travis-ci.org/espnet/espnet)


See https://espnet.github.io/espnet/docker.html

### Tags

- Runtime: Base image for ESPnet. It includes libraries and Kaldi installation.
- GPU: Image to execute examples with GPU support.

### Ubuntu 18.04

Pytorch 1.7.1, No warp-ctc:

- [`cuda11.0-cudnn8` (*docker/prebuilt/gpu/11.0/cudnn8/Dockerfile*)](https://github.com/espnet/espnet/tree/master/docker/prebuilt/devel/gpu/11.0/cudnn8/Dockerfile)
