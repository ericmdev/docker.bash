## Docker: Bash

[Bash](https://www.gnu.org/software/bash/) scripts for managing [Docker](https://www.docker.com/) **images** and **containers**.

### Installation

    $ git clone <repo> <docker_project>/bin

### Usage

**Build**

Run the `docker-compose` [build](https://docs.docker.com/compose/reference/build/) command to build services in docker-compose.yml.

    $ . bin/build

*Services are built once and then tagged as project_service.

**Up**

Run the `docker-compose` [up](https://docs.docker.com/compose/reference/up/) command to build, (re)create, start, and attach to containers.

    $ . bin/up

**Access**

Access the bash shell of running docker container.

    $ . bin/build

**Env**

Run the `docker-machine` [env](https://docs.docker.com/machine/reference/env/) command to set environment variables.

    $ . bin/env
