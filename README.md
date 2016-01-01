## Docker: Bash

[Bash](https://www.gnu.org/software/bash/) scripts for managing [Docker](https://www.docker.com/) **images** and **containers**.

### Installation

    $ git clone <repo> <docker_project>/bin

### Usage

**Build**

    $ . bin/build

Runs `docker-compose build`: the [build](https://docs.docker.com/compose/reference/build/) command to build services in docker-compose.yml.

*Services are built once and then tagged as project_service.

**Up**

    $ . bin/up

Runs `docker-compose up`: the [up](https://docs.docker.com/compose/reference/up/) command to build, (re)create, start, and attach to containers.

**Access**

    $ . bin/access

Access the bash shell of running docker container.

**Env**

    $ . bin/env

Runs `docker-machine env`: the [env](https://docs.docker.com/machine/reference/env/) command to set environment variables.
