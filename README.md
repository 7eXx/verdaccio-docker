# Verdaccio Docker
This repository holds the docker compose file to deploy verdaccio

## Pre check
Create a copy of ***.env*** file  and fill it with custom values.

## TLDR
It mounts conf, plugins and storage folders in the container

## Pre-check
Docker compose is used to mount all verdaccio config, plugins and storage folders in the container.  
So make sure to have right permissions.
```sh
$ chown -R 10001:65533 verdaccio/
```