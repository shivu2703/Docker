FROM ubuntu:latest

WORKDIR /app

COPY . /app

RUN apt update && apt install -y nodejs npm

RUN node -v && npm -v

CMD ["node", "hello.js"]


