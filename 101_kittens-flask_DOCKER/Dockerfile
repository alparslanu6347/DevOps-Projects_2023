FROM nginx:latest
RUN apt-get update -y
COPY /myapp /usr/share/nginx/html
WORKDIR /myapp
EXPOSE 8090 	
CMD ["nginx", "-g", "daemon off;"]
