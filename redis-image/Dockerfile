# Use an existing docker image as a base
FROM alpine

# download, install dependencies
RUN apk add --update redis

#tell what to do when it starts
CMD [ "redis-server" ]