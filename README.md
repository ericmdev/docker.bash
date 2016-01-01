## Docker: Bash

[Bash](https://www.gnu.org/software/bash/) scripts for managing [Docker](https://www.docker.com/) **images** and **containers**.

### Installation

    $ git clone <repo> <docker_project>/bin

### Usage

**Up**

Run the `docker-compose up` [command](https://docs.docker.com/compose/reference/up/) to build, (re)create, start, and attach to containers.

    $ . bin/up

**Build**

Run the `docker-compose build` [command](https://docs.docker.com/compose/reference/build/) to build services in docker-compose.yml.

    $ . bin/build

*Services are built once and then tagged as project_service.

**Env**

Run the `docker-machine env` [command](https://docs.docker.com/machine/reference/env/) to set environment variables.

    $ . bin/env
