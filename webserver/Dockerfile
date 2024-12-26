FROM nginx:alpine

LABEL org.opencontainers.image.description="nginx web server demo app with NULIX content"

# uncomment for OTA update test
COPY webserver/index.html /usr/share/nginx/html/

### BUILD ###
# docker build -t ghcr.io/nulix/webserver:1.0 webserver

### PUSH TO REGISTRY ###
# docker push ghcr.io/nulix/webserver:1.0

### EXPORT IMAGE ###
# docker save webserver:1.0 | gzip > webserver-app-1.0.tar.gz

### IMPORT IMAGE ON TARGET ###
# docker load -i webserver-app-1.0.tar.gz
