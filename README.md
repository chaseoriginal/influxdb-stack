# influxdb-stack

Portainer stack `influxdb-stack` on ore-dock-102-1.

This stack was originally deployed outside Portainer with a plain
`docker compose up -d` in `/opt/influxdb-stack`. It is now managed by Portainer and
git-backed with auto-update every 15 minutes.

## Secrets

The compose references `${VAR}` values that live in the Portainer stack
environment. `.env.example` lists the required keys; the real values are
NOT committed here.

## Original deployment

    cd /opt/influxdb-stack && docker compose up -d
