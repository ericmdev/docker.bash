## Docker: Bin

[Bash](https://www.gnu.org/software/bash/) scripts for managing [Docker](https://www.docker.com/) **images** and **containers**.

### Installation

    $ git clone <docker.bin> <docker_project>/bin

### Usage

**Access**

    $ . bin/access

Accesses the bash shell of a running docker container.

**Build**

    $ . bin/build

Runs `docker-compose build`.

The [build](https://docs.docker.com/compose/reference/build/) command builds services in docker-compose.yml.

*Services are built once and then tagged as project_service.

**Containers**

    $ . bin/containers

Runs `docker ps -a`.

The [ps -a](https://docs.docker.com/engine/reference/commandline/ps/) command shows all containers.

**Destroy**

    $ . bin/destroy

Stops and deletes all containers and images.

**Env**

    $ . bin/env

Runs `docker-machine env`.

The [env](https://docs.docker.com/machine/reference/env/) command sets environment variables.

**Logs**

    $ . bin/logs

Logs of a docker container.

**Restart**

    $ . bin/restart

Runs `docker restart`.

Restarts a docker container.

**Up**

    $ . bin/up

Runs `docker-compose up`.

The [up](https://docs.docker.com/compose/reference/up/) command builds, (re)creates, starts, and attaches to containers.

