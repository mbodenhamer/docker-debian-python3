[//]: # (-*- markdown -*-)

[![](https://travis-ci.org/mbodenhamer/docker-debian-python3.svg?branch=master)](https://travis-ci.org/mbodenhamer/docker-debian-python3)

A Debian Python 3 base image with [depman](https://github.com/mbodenhamer/depman) and [yatr](https://github.com/mbodenhamer/yatr).

## Usage

To launch a container inside a Python session, run:

    $ docker run --rm -it -v `pwd`:/app mbodenhamer/debian-python3:latest


A container can also be launched with Python arguments, like so:

    $ docker run --rm -it -v `pwd`:/app mbodenhamer/debian-python3:latest python --version