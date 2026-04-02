FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/JLveerababu-cloud/expense-infra-dev/blob/main/expense-infra-dev.drawio.svg /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]