FROM mongo:3.6.6

COPY ./mongod.conf /etc/mongod.conf
RUN mkdir -p /var/lib/mongodb
RUN mkdir -p /var/log/mongodb

EXPOSE 27017
CMD mongod -f /etc/mongod.conf