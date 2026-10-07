# exercice-cicd

Docker Compose environment for a CI/CD exercise.

## Overview

The repository contains a single `docker-compose.yaml`. It starts several
CI/CD and cloud-emulation services on one shared network: Jenkins (server and
agent), GitLab, Gitea, LocalStack and a `prod` container, among others.

## Getting started

Run from the repository root:

```bash
docker compose up -d
docker compose down    # stop and remove the containers
```
