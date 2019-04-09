FROM docker/compose:1.24.0

RUN apk add curl \
    && apk add git \
    && apk add nodejs \
    && apk add nodejs-npm \
    && apk add yarn \
    && rm -rf /var/cache/apk/*

ENTRYPOINT [ "tail", "-f", "/dev/null" ]
