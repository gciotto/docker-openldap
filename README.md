# OpenLDAP Compose and Swarm file

This repository defines YAML files for deployment of a OpenLDAP server. Further information about the image can be found in [this link](https://github.com/osixia/docker-openldap).

## Deployment

Use [docker-compose](https://docs.docker.com/compose/) or [swarm](https://docs.docker.com/engine/swarm/) with the `docker-compose.yml` file to deploy the service. Don't forget to redefine the environment variables and volume paths!

## Systemd service file

A systemd service file is also provided to enable initialization on boot. To set it up, use the `Makefile` script also provided here.
