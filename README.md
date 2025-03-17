# Elasticsearch and Kibana Setup with Docker Compose to run elasticsearch and kibana simply for training

This repository provides a Docker Compose configuration for setting up **Elasticsearch** and **Kibana** for local development and testing purposes.

## Prerequisites

Before running this setup, ensure you have:

- Docker installed ([Get Docker](https://docs.docker.com/get-docker/))
- Docker Compose installed ([Install Docker Compose](https://docs.docker.com/compose/install/))

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/MehdiMatinfar/dockerized-elasticsearch-kibana && cd dockerized-elasticsearch-kibana
   

2. Start the services:
   ```bash
   docker-compose up -d

3. Access the services:

   Elasticsearch: http://localhost:9200

   Kibana: http://localhost:5601


