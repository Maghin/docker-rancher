# MerhylStudio
#
# Reverse proxy
#
## Redirects all http request to https request and redirects them
## on rancher target by http
FROM httpd:2.4-alpine

MAINTAINER "Adrien Estanove" <maghin@merhylstudio.org>

COPY ./conf "$HTTPD_PREFIX/conf"

# Expose httpd port with ssl support
EXPOSE "4343"

