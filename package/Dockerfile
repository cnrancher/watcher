FROM alpine:3
RUN apk update
RUN apk add curl
COPY bin/watcher /watcher
CMD ["/watcher"]