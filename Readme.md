# Nostr relay to be used behind nginx or cloudflared

## Basic requirements

1. An nginx server (docker or otherwise) configured as a reverse proxy or a cloudlare tunnel with its associated docker
2. docker network with the required names

Edit the docker compose yaml file and the config.toml with parameters as per your requirement and run docker-compose up -d and you should be ready to go.
