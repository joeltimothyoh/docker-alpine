ARG IMAGE
FROM $IMAGE

RUN apk update \
    && apk add --no-cache curl \
    && rm -rf /var/cache/apk/*

CMD ["/bin/sh"]