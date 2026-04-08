FROM almalinux:9
CMD ['ping', 'google.com']
RUN dnf install git -y
RUN dnf install nginx -y
RUN useradd gvrao
USER gvrao
