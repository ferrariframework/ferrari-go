FROM golang:alpine

RUN wget https://github.com/ferrariframework/ferrariworker/releases/download/0.6.0/ferrariworker.linux-amd64.tar.gz && \
    tar zxf ferrariworker.linux-amd64.tar.gz -C /usr/local/bin && \
    rm ferrariworker.linux-amd64.tar.gz

ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["ferrariworker"]
