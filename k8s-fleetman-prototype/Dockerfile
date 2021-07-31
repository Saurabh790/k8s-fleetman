FROM nginx:1.14.0-alpine

MAINTAINER Saurabh Gupta  "saurabh.gupta90@outlook.com"

RUN rm -rf /usr/share/nginx/html/*

COPY /dist /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]
