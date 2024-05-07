FROM alpine

RUN apk add rsync

COPY ./alpine-mirror /app/alpine-mirror

RUN mkdir /data && mkdir /data/alpine
RUN chmod +x /app/alpine-mirror

ENTRYPOINT ["/app/alpine-mirror"]