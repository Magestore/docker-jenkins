FROM docker/compose:1.23.2

RUN apk add curl \
    && apk add git \
    && apk add nodejs \
    && apk add nodejs-npm \
    && rm -rf /var/cache/apk/*

ENTRYPOINT [ "tail", "-f", "/dev/null" ]
