FROM haproxy:1.6

RUN apt-get update && apt-get install -y curl links
COPY ./haproxy/haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg