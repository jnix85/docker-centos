# docker-centos

## Description

This is just the official [centos](https://hub.docker.com/_/centos) image from the Docker Hub. No modifications have been made, excluding the CentOS Stream container (which is built from CentOS 8 with distro-sync). 

Pretty much all i'm doing is running yum/dnf upgrade and installing epel-release here. 

## Usage

```shell
docker run --rm -it jnix85/centos:$tag bash
```

