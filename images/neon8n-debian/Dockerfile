FROM naskio/n8n-python:latest-debian

WORKDIR /usr/lib/node_modules/n8n
RUN npm install n8n-nodes-changed
RUN npm install n8n-nodes-updates
RUN npm install n8n-nodes-influxdb

RUN apt-get update
RUN apt-get -y install mariadb-client
