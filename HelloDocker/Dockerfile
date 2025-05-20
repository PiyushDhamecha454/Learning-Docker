FROM ubuntu:20.04
RUN apt-get update && apt-get install -y curl
COPY . /app
WORKDIR /app
CMD ["echo", "Hello, Docker!"]