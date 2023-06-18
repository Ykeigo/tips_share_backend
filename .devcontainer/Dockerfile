FROM golang:1.20-bullseye
#FROM golang:1.14-alpine

# https://dev.classmethod.jp/articles/db-migrate-with-golang-migrate/
RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y curl gnupg2 vim
RUN curl -L https://github.com/golang-migrate/migrate/releases/download/v4.11.0/migrate.linux-amd64.tar.gz | tar xvz
RUN mv ./migrate.linux-amd64 /usr/bin/migrate