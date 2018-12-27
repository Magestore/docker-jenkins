FROM docker/compose:1.23.1

RUN apk add curl \
    && apk add git \
    && apk add nodejs \
    && apk add nodejs-npm \
    && apk add python \
    && rm -rf /var/cache/apk/*

ENTRYPOINT [ "tail", "-f", "/dev/null" ]
