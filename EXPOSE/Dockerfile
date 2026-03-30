FROM almalinux:9
RUN dnf install -y nginx
RUN useradd murthy
LABEL  "Name"="Murthy" \
       "SurName"="Ch" \
       "Qual"="MTech" 
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]
