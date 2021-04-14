ARG VERSION=1.16.3 

FROM golang:${VERSION}-alpine As build

ENV GO111MODULE=on

RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh vim

WORKDIR /var/www

CMD ["/start.sh"]
