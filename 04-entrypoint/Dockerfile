FROM        docker.io/redhat/ubi9:latest
RUN         dnf install nginx -y
COPY        index.html /usr/share/nginx/index.html
ENTRYPOINT  ["nginx", "-g", "daemon off;"]

