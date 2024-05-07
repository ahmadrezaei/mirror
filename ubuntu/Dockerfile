FROM alpine

RUN apk add rsync

COPY ./ubuntu-mirror /app/ubuntu-mirror

RUN mkdir /data && mkdir /data/alpine
RUN chmod +x /app/ubuntu-mirror

ENTRYPOINT ["/app/ubuntu-mirror"]