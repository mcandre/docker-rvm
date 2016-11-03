# docker-rvm - a Docker container for RVM

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-rvm/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-rvm:latest rvm --version
rvm 1.26.11 (latest) by Wayne E. Seguin <wayneeseguin@gmail.com>, Michal Papis <mpapis@gmail.com> [https://rvm.io/]
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
