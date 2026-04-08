FROM almalinux:9
RUN mkdir /tmp/workdir-demo
#RUN cd /tmp/workdir-demo
WORKDIR cd /tmp/workdir-demo
RUN pwd
RUN echo "hello i am in work dir" >hello.txt
CMD ["sleep", "infinity"]
# docker build -t workdir:v1 --no-cache --progress=plain . {this command will build the docker image with the name workdir and tag v1 without using cache and showing the progress in plain format.}