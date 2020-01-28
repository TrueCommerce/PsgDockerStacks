# DevOps NetSuite Sync

Internal service that keeps NetSuite issue and DevOps work items in sync based on custom TypeScript rules and mappings.

## Deployment

This app is deployed as two identical containers. One handles events from the production NetSuite and DevOps accounts and the other handles events from the sandbox NetSuite and DevOps accounts. This approach allows users to test their TypeScript mappings in sandbox before deploying them to production.

```bash
git clone --depth 1 --no-checkout https://github.com/truecommerce/psgdockerstacks .
git checkout master -- devopsnetsuitesync
cd devopsnetsuitesync
docker-compose up -d
```
