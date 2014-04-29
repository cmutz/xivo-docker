Dockerfile for XiVO

## Warning

This dockerfile install XiVO in dev version.

## Build

To build the image, simply invoke

    docker.io build -t xivo-dev github.com/sboily/xivo-docker

A prebuilt container is also available in the docker index

    docker.io pull quintana/xivo-docker
  
## Usage

To run the container, do the following:

    docker.io run -d -P quintana/xivo-docker

or
    docker.io run -i -t quintana/xivo-docker /bin/bash

or
    docker.io run -i -t  xivo-dev /bin/bash

If you want to using a simple webi to administrate docker use : https://github.com/crosbymichael/dockerui
