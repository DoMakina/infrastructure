# DoMakina Infrastructure

This repository contains the infrastructure setup for the DoMakina project. It includes the configuration for various services required to run the application.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Starting the Containers](#starting-the-containers)
- [Stopping the Containers](#stopping-the-containers)
- [Services](#services)
- [Volumes](#volumes)
- [Networks](#networks)

## Prerequisites

Ensure you have the following software installed on your system:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Setup

Before starting the containers, make sure to configure any necessary environment variables and files.

## Starting the Containers

To start the containers, run the following command:

```bash
docker compose up -d --build
```

## Open shell inside container

```bash
docker exec -it <container_id_or_name> /bin/sh
```
