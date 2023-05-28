# Traefik sample config and docker-compose file

## Generate password for traefik users
```bash
echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g
```