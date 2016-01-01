## Docker: Bin

[Bash](https://www.gnu.org/software/bash/) scripts for managing [Docker](https://www.docker.com/) **images** and **containers**.

### Installation

    $ git clone <docker.bin> <docker_project>/bin

### Usage

**Build**

    $ . bin/build

Runs `docker-compose build`.

The [build](https://docs.docker.com/compose/reference/build/) command builds services in docker-compose.yml.

*Services are built once and then tagged as project_service.

**Up**

    $ . bin/up

Runs `docker-compose up`.

The [up](https://docs.docker.com/compose/reference/up/) command builds, (re)creates, starts, and attaches to containers.

**Access**

    $ . bin/access

Accesses the bash shell of a running docker container.

**Logs**

    $ . bin/logs

Logs of a docker container.

**Env**

    $ . bin/env

Runs `docker-machine env`.

The [env](https://docs.docker.com/machine/reference/env/) command sets environment variables.
