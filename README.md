## Docker: Bash

[Bash](https://www.gnu.org/software/bash/) scripts for managing [Docker](https://www.docker.com/) **images** and **containers**.

### Installation

    $ git clone <repo> <docker_project>/bin

### Usage

Build, (re)create, start, and attach to containers.

    $ . bin/up


Access the Bash shell of a running Docker container:

    $ . bin/access <container_name>

Bash file extensions are considered redundant. To find out file use:

    file scriptname