FROM nginx:1.22

WORKDIR /workspace

ENV TZ=UTC

COPY ./infra/docker/nginx/*.conf /etc/nginx/conf.d/

# RUN apk update && apk add --update --no-cache --virtual=.build-dependencies \
# && apk add --no-cache --virtual g++ \
# && apk add --no-cache libstdc++ && apk add --no-cache libgcc \
# && apk -UvX http://dl-4.alpinelinux.org/alpine/edge/main add -u nodejs npm

# RUN apt-get update
# RUN apt-get install nodejs

# RUN apt update
# RUN apt install nodejs
# RUN apt install npm
