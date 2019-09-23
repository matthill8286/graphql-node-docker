### tech check
* Node v8+
* Yarn / NPM (latest)
* Mongo (latest) (see below for Docker install)
* Git + Github

## MongoDB with Docker

* Install [Docker](https://www.docker.com/community-edition).
* Run:

```shell
$ docker run -p 27017:27017 -d mongo
