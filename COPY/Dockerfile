FROM almalinux:9
RUN dnf install -y nginx
RUN rm -f /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
LABEL  "Name"="Murthy" \
       "SurName"="Ch" \
       "Qual"="MTech" 
EXPOSE 8082
CMD ["nginx", "-g", "daemon off;"]
