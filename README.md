# PSG Docker Stacks

This repo contains docker compose files for internally-developed and 3rd-party containers that are used or maintained by PSG Engineering.

## How to Deploy

1. SSH into the server you want to deploy to.

2. Clone this repo using `git clone https://github.com/truecommerce/psgdockerstacks`.

3. Copy the `docker-stacks.yml` file from the appropriate subfolder (ex. `mv ./psgdockerstacks/my-server/docker-compose.yml ./docker-compose.yml`).

4. Use `docker-compose up -d` to stand up your container(s).
