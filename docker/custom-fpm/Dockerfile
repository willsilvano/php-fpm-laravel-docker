FROM trafex/alpine-nginx-php7:latest

USER root

RUN apk --no-cache add php7-redis php7-tokenizer

# Switch to use a non-root user from here on
USER nobody

