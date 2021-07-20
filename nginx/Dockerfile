FROM nginx:latest
COPY index.html /usr/share/nginx/html/index.html
USER root
RUN mkdir /opt/share && ln -s /opt/share /usr/share/nginx/html/ 
