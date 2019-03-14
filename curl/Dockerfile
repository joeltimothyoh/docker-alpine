ARG BASE_IMAGE
FROM $BASE_IMAGE

RUN apk update \
    && apk add --no-cache curl \
    && rm -rf /var/cache/apk/*

CMD ["/bin/sh"]