# Deployment Of Traefik on Docker

<p>This project deploy docker and traefik containers:</p>
<li>Deploy traefik as a reverse proxy.</li>
<li>2 "containous/whoami" containers are deployed</li>
<li>The containers come to register with traefik</li>
<li>Mapping of dynamic ports between traefik and whoami containers</li>
<li>Each container must be able to respond to its own domain (ex: container 1 must respond to first.localhost and container 2 to second.localhost)</li>
