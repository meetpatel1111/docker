FROM ubuntu:20.04

WORKDIR /app

RUN cd .. && ls -la

COPY . .

RUN apt-get update && apt-get install -y curl nano

CMD [ "bash" ]