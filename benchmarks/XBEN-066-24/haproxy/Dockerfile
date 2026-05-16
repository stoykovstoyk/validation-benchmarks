FROM haproxy:2.0-alpine

<<<<<<< HEAD
RUN apk add --no-cache curl 
=======
RUN sed -i 's/deb.debian.org/archive.debian.org/g' /etc/apt/sources.list && \
    sed -i 's/security.debian.org/archive.debian.org/g' /etc/apt/sources.list && \
    sed -i '/buster-updates/d' /etc/apt/sources.list && \
    apt-get update && apt-get install -y curl 
>>>>>>> pr-11

COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg
