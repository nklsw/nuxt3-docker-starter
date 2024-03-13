# Dockerized Nuxt 3 Starter

Working with Docker containers is a convinient way to seperate local machines ressources and configuration from development environments. This minimal project is a starter for creating dockerized [Nuxt 3](https://github.com/nuxt/framework) applications.

## Prerequisites

Make sure that [docker](https://docs.docker.com/get-docker/) and [docker-compose](https://docs.docker.com/compose/install/) are installed on your local machine.

## Setup

Start the development server on http://localhost:3000

```bash
docker compose up
```


## Production 
🚧 WIP

Build the docker container for production:

```bash
docker build -t nuxt_build .
```

Run nuxt build inside the container:

```bash
docker run -it nuxt_build npm run build
```

Checkout the official Nuxt 3 [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
