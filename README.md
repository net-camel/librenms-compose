# LibreNMS

## Deploy Instructions
1. Edit _.env\_template_ and rename to _.env_.
2. Edit _docker-compose.yaml_ to update the expected URL for the librenms service. Check both envrionment variable and Traefik labels.
3. Confirm Traefik is running and the docker _frontend_ network has been created.
4. Run `docker compose up -d`.

