# Rocket.Chat with SSL Certificate in a Docker Swarm

Configure Traefik before applying the configuration.

Traefik configuration: https://github.com/heyValdemar/traefik-ssl-certificate-docker-swarm

Deploy Rocket.Chat in a Docker Swarm using the command:

`docker stack deploy -c rocketchat-traefik-ssl-certificate-docker-swarm.yml rocketchat`
