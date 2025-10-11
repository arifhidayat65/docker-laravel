FROM nginx:1.28.0-alpine3.21-slim

WORKDIR /workspace

ENV TZ=UTC

COPY ./infra/docker/nginx/*.conf /etc/nginx/conf.d/
