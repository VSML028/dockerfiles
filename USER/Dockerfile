FROM almalinux:9
CMD ['ping', 'google.com']
RUN dnf git install -y
RUN dnf install -y python3
RUN dnf install nginx -y
RUN useradd gvrao
USER gvrao
