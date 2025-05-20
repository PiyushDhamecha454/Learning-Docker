FROM alpine:latest

WORKDIR /usr/src/app

COPY hello.sh .

COPY additional.txt .


RUN chmod +x hello.sh

RUN touch new.txt

CMD ["./hello.sh"]