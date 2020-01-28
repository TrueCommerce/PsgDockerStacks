# Seq

Seq is a 3rd-party container that provides a structured logging server used by all PSG apps.

## Deployment

```bash
git clone --depth 1 --no-checkout https://github.com/truecommerce/psgdockerstacks .
git checkout master -- seq
cd seq
docker-compose up -d
```
