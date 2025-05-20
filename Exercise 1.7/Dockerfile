FROM ubuntu:latest

RUN apt-get update && apt-get install curl -y

WORKDIR /usr/src/app

COPY script.sh .

RUN chmod +x script.sh

CMD ["./script.sh"]