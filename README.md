# PSG Docker Stacks

This repo contains docker compose files for internally-developed and 3rd-party containers that are used or maintained by PSG Engineering.

## How to Deploy

1. SSH into the server you want to deploy to (ex. `$ ssh user@server.tcpsg.net`).

2. Clone this repo using `$ git clone https://github.com/truecommerce/psgdockerstacks`.

3. Copy the `docker-compose.yml` file from the appropriate subfolder (ex. `$ mv ./psgdockerstacks/vm00/docker-compose.yml ./docker-compose.yml`).

4. Ensure you have a `.env` file in place with any variables required by the particular compose file you've chosen. You can use `$ nano .env` to check the file.

5. Use `$ docker-compose up -d` to stand up your container(s).

## Servers

This repo contains a docker compose file for each server in the PSG Engineering environment.

* **[localhost](/localhost):** Local development environment for sandboxing new containers.

* **[VM00](/VM00):** Internal and other low-demand apps and services.
* **[VM01](/VM01):** TrueCommerce University (Q4 2020)
