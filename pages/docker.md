
# Docker

## Access localhost from docker container

- https://stackoverflow.com/questions/24319662/from-inside-of-a-docker-container-how-do-i-connect-to-the-localhost-of-the-mach
  - Use `--network="host"` in your `docker run` command, then `127.0.0.1` (or `localhost`) in your docker container will point to your docker host.


