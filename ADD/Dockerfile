FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
RUN chmod+r /usr/share/nginx/html/index.html
ADD http://https://github.com/daws-84s/notes/blob/main/session-05.txt /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
