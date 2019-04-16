# Use an existing docker image as a base
FROM alpine

# Download and install dependencies
RUN apk add --update redis

# Add other dependency
RUN apk add --update gcc

# Tell an image what to do when it starts as a container
CMD ["redis-server"]