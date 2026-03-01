FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD https://github.com/VSML028/Training_Documents/blob/main/Jenkins/Class_Notes.txt /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
