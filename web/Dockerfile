from nginx:latest

copy ./web/src /usr/share/nginx/html

expose 80

cmd ["nginx", "-g", "daemon off ;"]
