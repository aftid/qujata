FROM openquantumsafe/nginx:latest

# NodeJS version > 14 requires not being in root directory while npm install
WORKDIR /usr/app

ADD nginx.conf /opt/nginx/nginx-conf/nginx.conf
ADD app.js app.js
ADD start.sh start.sh

USER root

RUN apk add --update nodejs npm
RUN npm install express
RUN chmod +x start.sh

USER oqs



CMD ["./start.sh"]
