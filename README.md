# docker-caddy
Docker for Caddy webserver - Build from the source, using alpine

More information about usage will be posted soon...

##### Run the image

You may change the ports if the ports 80 and 443 are not available on your host.

$ docker run -d \
    -v $(pwd)/Caddyfile:/etc/Caddyfile \
    -p 80:80 -p 443:443 \
    geofox/docker-caddy
