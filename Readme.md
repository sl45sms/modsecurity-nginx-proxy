The aim for this is to compine nginx-proxy with Modsecurity
build with:
docker build -t modsecurity/nginx-proxy:latest .


The provided nginx.tpl here contains a modification to allow IP attribute on containers.
Also contains a way to rewrite root location by placing a domainname_locations file (with s at end) 
that need to contain a root location.
```
location / {
    ....
}
```
for enviroment variables for Modsecurity look at https://hub.docker.com/r/owasp/modsecurity-crs
for nginx-proxy look at https://hub.docker.com/r/jwilder/nginx-proxy