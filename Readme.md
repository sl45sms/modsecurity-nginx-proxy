The aim for this is to compine nginx-proxy with Modsecurity
build with:
docker build -t modsecurity/nginx-proxy:latest .


The provided nginx.tpl here contains a modification to allow IP attribute on containers.

for enviroment variables for Modsecurity look at https://hub.docker.com/r/owasp/modsecurity-crs
for nginx-proxy look at https://hub.docker.com/r/jwilder/nginx-proxy