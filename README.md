# docker-helloworld

[![Docker Image CI](https://github.com/crajapakshe/docker-helloworld/actions/workflows/docker-image.yml/badge.svg?branch=main)](https://github.com/crajapakshe/docker-helloworld/actions/workflows/docker-image.yml) [![Publish Docker image](https://github.com/crajapakshe/docker-helloworld/actions/workflows/build-publish.yml/badge.svg)](https://github.com/crajapakshe/docker-helloworld/actions/workflows/build-publish.yml)

![Docker Pulls](https://img.shields.io/docker/pulls/crajapakshe429/helloworld.svg) ![Automated Builds](https://img.shields.io/docker/automated/crajapakshe429/helloworld.svg) ![Build Status](https://img.shields.io/docker/cloud/build/crajapakshe429/helloworld.svg )

A simple helloworld app for docker

A simple nginx helloworld application that helps you learn docker image pulls. Runs on port `:80`

To pull this image:
```bash
docker pull crajapakshe429/helloworld:latest
```

To run this image:
```bash
docker run -p 8080:80/tcp "crajapakshe429/helloworld:latest"
```

Dockerhub link: https://hub.docker.com/r/crajapakshe429/helloworld/

Github link: https://github.com/crajapakshe/docker-helloworld
