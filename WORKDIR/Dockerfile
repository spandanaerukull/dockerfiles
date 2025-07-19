FROM almalinux:9
RUN mkdir /tmp/workdir-demo
# RUN  cd /tmp/workdir-demo
WORKDIR /tmp/workdir-demo 
# this will change the directory for all the below commands
RUN pwd
RUN echo "hello from workdir demo" > hello.txt
CMD ["sleep", "2000"]