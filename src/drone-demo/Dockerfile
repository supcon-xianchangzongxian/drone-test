FROM golang:1.10.2
ADD drone-demo /root/drone-demo
RUN chmod u+x /root/drone-demo
RUN mkdir -p /var/log/demo63
CMD ./root/drone-demo >> /var/log/demo63/dd63.log 2>&1
EXPOSE 7070