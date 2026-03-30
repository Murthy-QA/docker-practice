FROM almalinux:9
RUN dnf install -y nginx
RUN useradd murthy
LABEL  "Course"="DevOps" \
       "Trainer"="Siva" \
       "Trainee"="Murthy" \
       "Duration"="100Hrs"
CMD ["nginx", "-g", "daemon off;"]