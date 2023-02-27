# DecisionRules

[DecisionRules](https://www.decisionrules.io/): Agile Business Rule Engine for every industry.

## Overview

### Generate DecisionRules License Key
Please use [DecisionRules License Key Generator](https://www.decisionrules.io/on-premise#license). The generator will send your trial license key to your email. **Note**: After registration, you are ready to use DecisionRules for 30 days as you like.

Put your license key in the `env.example` file and rename it to `.env` and then place the `.env` file under the folder where the `docker-compose.yml` files are.

### Resources

* [Documentation](https://docs.decisionrules.io/doc/)
* [Environment Variables](https://docs.decisionrules.io/doc/on-premise-docker/containers-environmental-variables)
* [Kubernetes Setup](https://docs.decisionrules.io/doc/on-premise-docker/kubernetes-setup)

## Showcase app

[Client Server Showcase App](https://docs.decisionrules.io/doc/on-premise-docker/showcase-client-server-app/showcase)

### Download the compose file

```
curl -L https://decisionrules.io/showcase/docker-compose.yml --output docker-compose.yaml
```

### Run

```
docker compose up
```

After this, you can enter `localhost:80` and you will be redirected to the login page of the DecisionRules login screen. Either create a new local account or use the existing account: `demo@test.com` / `Demotest1`.


## Business Intelligence app

[Business Intelligence App](https://docs.decisionrules.io/doc/on-premise-docker/showcase-client-server-app/showcase-+-business-intelligence)

### Download the compose file

```
curl -L https://decisionrules.io/showcase-with-business-intelligence/docker-compose.yml --output docker-compose.yaml
```

### Run

```
docker compose up
```

After this, you can enter `localhost:80` and you will be redirected to the login page of the DecisionRules login screen. Either create a new local account or use the existing account: `demo@test.com` / `Demotest1`.