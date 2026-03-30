FROM almalinux:9
RUN dnf install -y nginx
RUN useradd murthy
LABEL  "Name"="Murthy" \
       "SurName"="Ch" \
       "Qual"="MTech" 
CMD ["nginx", "-g", "daemon off;"]