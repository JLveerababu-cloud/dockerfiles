FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/JLveerababu-cloud/expense-infra-dev/blob/main/expense-infra-dev.drawio.svg /usr/share/nginx/html/index.html
RUN chmod 644 /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]