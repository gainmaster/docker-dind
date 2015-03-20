# Docker DIND

[![Build Status](http://jenkins.hesjevik.im/job/docker-dind/badge/icon)](http://jenkins.hesjevik.im/job/docker-dind/) [![Docker Hub](https://img.shields.io/badge/docker-ready-blue.svg?style=plastic)](https://registry.hub.docker.com/u/bachelorthesis/dind/)

This repository contains a **Dockerfile** for a Docker in docker image, a **Vagrantfile** for local development, and **shell scripts** for easy startup of container taks. This repository is a part of an automated build, published to the [Docker Hub][docker_hub_repository].

**Base image:** [scratch][docker_hub_base_image]

[docker_hub_repository]: https://registry.hub.docker.com/u/bachelorthesis/dind/
[docker_hub_base_image]: https://registry.hub.docker.com/_/scratch/

## Resources

These resources have been helpful when creating this repository:

* [Docker Blog - Docker can now run within Docker][docker_blog_dind]
* [jpetazzo's Github repository with a Docker in Docker image][github_jpetazzo_dind]

[docker_blog_dind]: https://blog.docker.com/2013/09/docker-can-now-run-within-docker/
[github_jpetazzo_dind]: https://github.com/jpetazzo/dind