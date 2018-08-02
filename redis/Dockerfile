FROM redis:4.0.10

COPY redis.conf /redis/redis.conf
RUN mkdir -p /var/lib/redis/

EXPOSE 6379
CMD redis-server /redis/redis.conf