FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
ADD https: //github.com/JLveerababu-cloud/terraform-aws-ec2/blob/main/readme.MD
CMD ["nginx", "-g", "daemon off;"]