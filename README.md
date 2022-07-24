# Deployment Of Traefik on Docker
This project deploy docker and traefik containers:
• Deploy traefik as a reverse proxy
• 2 "containous/whoami" containers are deployed
• The containers come to register with traefik
• Mapping of dynamic ports between traefik and whoami containers
• Each container must be able to respond to its own domain (ex: container 1 must respond to first.localhost and container 2 to second.localhost
