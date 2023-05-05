
FROM ubuntu:latest
RUN apt update && apt install -y redis-server
EXPOSE 6380/tcp
COPY redis.conf /etc/redis/ 
CMD redis-server /etc/redis/redis.conf
USER redis
LABEL MANTAINER="Luca Bragante"
