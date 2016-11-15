# docker-haproxy
Docker image with haproxy

You must provide your own haproxy.cfg at the volume location /etc/haproxy/ 
or you can add the following line to the Dockerfile to insert the config at
build time.

COPY haproxy.cfg /etc/haproxy/haproxy.cfg
