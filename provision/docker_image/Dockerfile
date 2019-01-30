# Version: 0.0.1
FROM debian:8.5
MAINTAINER maintainer_name "maintainer_email"
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Hello World' \
>/usr/share/nginx/html/index.html
EXPOSE 80
ENTRYPOINT ["nginx", "-g", "daemon off;"]
