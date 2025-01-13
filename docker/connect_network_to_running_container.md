# Create a new docker network and connect a running container to it

I needed to connect some docker containers to a reverse proxy without shutting them down.  I created the new proxy network `docker network create proxy` then used `docker network connect $container $network` to add them to the proxy network.
