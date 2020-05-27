# VM00

## Apps and Services on this Server

| App/Service | Public UI or API? |
|:-----------:|:-----------------:|
| DevOps NetSuite Sync Service (Live) | No |
| DevOps NetSuite Sync Service (Sandbox) | No |
| NetSuite Datalake Ingestion Service | No |
| PostOffice Email Template Manager | Yes |
| Seq Logging Server | Yes |

## Supporting Services on this Server

| App/Service | Public UI or API? |
|:-----------:|:-----------------:|
| Portainer | Yes |
| PostgreSQL | No |
| Traefik | Yes\* |

> \* Traefik is a reverse proxy and thus accepts traffic for all other services on this server through port 80 and 443.
